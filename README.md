# CoRecruit Project

## Description
This project leverages a vast dataset from [Jobtech](https://www.jobtechdev.se/en), containing all job postings from Arbetsförmedlingen, to train an AI aimed at improving recruiters' job listings. By using scientific articles on recruiting to create an initial dataset, the project refines a version of ChatGPT to specifically recommend enhancements to job descriptions. The application, hosted on streamlit.io, serves as a practical tool for recruiters to generate more effective job postings based on AI-driven suggestions, improving the recruitment process through advanced machine learning techniques.

## Getting Started with VS Code

To contribute to or use this project, you'll need Visual Studio Code installed on your machine or another IDE to work with Python/CSS. Follow these instructions to clone the project, set up your environment, and start contributing.

### Prerequisites
- Install [Visual Studio Code](https://code.visualstudio.com/)
- Git installed on your machine

### Installation

#### Clone the Repository
1. Open VS Code, press `Ctrl+Shift+P` to open the command palette, and type `Git: Clone`.
2. Enter the URL `https://github.com/BarreBN/CoRecruit.git` and select a local directory.

#### Open the Project
- Open the cloned project folder in VS Code.

#### Install Dependencies
1. Open the terminal in VS Code by pressing `Ctrl+`` or selecting `Terminal > New Terminal` from the menu.
2. To install the necessary project dependencies, run the following command:
   ```bash
   pip install -r requirements.txt

### Usage
To use this project in VS Code, follow these steps:
1. Open VS Code and navigate to the project directory.
2. Open the terminal by pressing `Ctrl+`` or selecting `Terminal > New Terminal` from the menu.
3. Run the Streamlit application by executing the following command:
   ```bash
   streamlit run app.py


## Contributing
1. **Fork the Repository**
   - Visit the GitHub page of the project and click "Fork" at the top right to create a fork under your GitHub account.
2. **Clone Your Forked Repository in VS Code**
   - Open VS Code, press `Ctrl+Shift+P` to open the Command Palette, type `Git: Clone`, and enter the URL of your fork. Choose a local directory to clone the repository into.
3. **Switch to the Development Branch**
   - Open the integrated terminal in VS Code (`Ctrl+``) and switch to the `dev` branch, our primary branch for development:
     ```
     git checkout dev
     ```
   - If it's your first time checking out the `dev` branch, you may need to fetch it from the origin first:
     ```
     git fetch origin dev:dev
     git checkout dev
     ```
4. **Create Your Feature Branch**
   - Still in the integrated terminal, create and switch to a new branch for your contribution:
     ```
     git checkout -b feature/YourFeatureName
     ```
   - Replace `YourFeatureName` with a short but descriptive name of the feature or fix you are contributing.

5. **Make Your Changes**
   - Use VS Code to make your changes. Remember to save your files.

6. **Commit Your Changes**
   - Once you're satisfied with your changes, stage them in VS Code's Source Control panel.
   - Use the commit message box to describe your changes and click the checkmark above to commit. For a detailed message, press `Ctrl+Enter` in the message box.

7. **Push Your Changes**
   - Push your changes by opening the Command Palette with `Ctrl+Shift+P`, type `Git: Push`, and execute the command. If you created a new branch, VS Code might ask you to configure the upstream; accept it.

8. **Open a Pull Request**
   - Go to your fork on GitHub, find your new branch, and click "Pull Request" to initiate one against the original repository's `dev` branch. Fill in the details about your changes and submit.

## Team
- Brandon
- Jakob
- Molly
- Peter
- Tobias
