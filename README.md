# Alura - Back-End Immersion

This is the repository for the front-end of the project.

**IMPORTANT:** You must have [Node.js](https://nodejs.org/) installed on your computer before running the project installation and execution commands. Recommended version: v20.x.x.

## STEP 1: Download the project code:

### Option 1 - Cloning the repository to your GitHub profile

> To use this option, you need to have [Git](https://git-scm.com/downloads) installed and configured on your computer. If it is not installed or you are unsure, proceed with **Option 2** and download the project as a .zip file.

1. **Fork** the project by clicking the **Fork** button in the upper right corner of the page;
2. Clone the repository to your computer:
   - Click the **<> Code** button and copy the remote repository URL;
   - Open the terminal, navigate to the root folder where you want to download the project, and run the command `git clone <remote URL>`;
   - You can access the project folder directly in Visual Studio Code by clicking on `File > Open Folder` and selecting the project folder.

### Option 2 - Downloading a .zip file

1. Click the **<> Code** button, then the **Download ZIP** button;
2. A zipped folder will be downloaded to the downloads folder specified by your browser;
3. Extract the files by clicking on the zipped folder icon and move the files to your preferred project folder.

---

## STEP 2: Install the project:

### Option 1 - Using the Visual Studio Code terminal

1. Open the project folder in Visual Studio Code by clicking on `File > Open Folder` and selecting the project folder;
2. Click on `Terminal > New Terminal` in the top menu of Visual Studio Code. The terminal should open, already pointing to the correct project folder;
3. Run the command `npm install` and wait for the process to complete.

### Option 2 - Using other terminals

1. Open your preferred terminal and navigate to the project folder using navigation commands like `cd <folder>`;
2. With the prompt pointing to the project folder root, run the command `npm install` and wait for the process to complete.

---

## STEP 3: Run the project to start the local server:

Open the terminal (Visual Studio Code terminal or any other terminal), ensure it points to the correct project folder, and run the command `npm run dev`. The terminal should return:

dev npx parcel --port 8000 index.html

Server running at http://localhost:8000 ✨ Built in xxxms


The project will be available at http://localhost:8000, and you can access it in your preferred browser.
