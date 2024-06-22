[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282299&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   answer:
   windows 11
   _Step 1: Check System Requirements_

- Go to Microsoft's website to check if your computer meets the system requirements for Windows 11.
- Click on the "Download now" button to proceed.

_Step 2: Download the Media Creation Tool_

- Click on the "Download tool now" button to download the Media Creation Tool.
- Save the file to your computer (e.g., "MediaCreationTool.exe").

_Step 3: Run the Media Creation Tool_

- Double-click the downloaded file to run the tool.
- Accept the terms and conditions.

_Step 4: Select Language and Edition_

- Choose your language and edition of Windows 11.
- Click "Next".

_Step 5: Choose Installation Method_

- Select "USB drive" or "ISO file" as the installation method.
- Click "Next".

_Step 6: Create Installation Media_

- select a location to save the ISO file.
- Click "Next".

_Step 7: Download Windows 11_

- The tool will download the Windows 11 installation files.
- This may take some time depending on your internet connection.

_Step 8: Create a Bootable USB Drive_

- If using a USB drive, the tool will create a bootable drive.
- Remove the USB drive when prompted.

_Step 9: Boot from the USB Drive_

- Insert the USB drive into the computer you want to install Windows 11 on.
- Restart the computer and press the appropriate key (e.g., F2, F12) to access the boot menu.
- Select the USB drive as the boot device.

_Step 10: Start the Installation_

- The Windows 11 installation wizard will start.
- Follow the prompts to complete the installation process.

_Step 11: Activate Windows 11_

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/

   answer:

   _Notepad++:_

1. _Download_: Go to the Notepad++ website and click on the "Download" button.
1. _Choose the version_: Select the appropriate version (32-bit or 64-bit) that matches your system architecture.
1. _Run the installer_: Double-click the downloaded file (e.g., `npp.8.4.8.Installer.exe`) to run the installer.
1. _Follow the prompts_: Click "Next" to accept the terms and conditions, then choose the installation location and whether to install the themes and plugins.
1. _Choose the default language_: Select your preferred language and click "Next".
1. _Choose the default encoding_: Select the encoding you want to use (e.g., UTF-8) and click "Next".
1. _Install_: Click "Install" to begin the installation process.
1. _Finish_: Click "Finish" to launch Notepad++.

_Visual Studio Code:_

1. _Download_: Go to the Visual Studio Code website and click on the "Download" button.
2. _Choose the version_: Select the appropriate version (32-bit or 64-bit) that matches your system architecture.
3. _Run the installer_: Double-click the downloaded file (e.g., `VSCodeSetup-1.74.2.exe`) to run the installer.
4. _Follow the prompts_: Click "Next" to accept the terms and conditions, then choose the installation location and whether to install the extensions and settings.
5. _Choose the default language_: Select your preferred language and click "Next".
6. _Choose the default theme_: Select the theme you want to use (e.g., Light or Dark) and click "Next".
7. _Install_: Click "Install" to begin the installation process.
8. _Finish_: Click "Finish" to launch Visual Studio Code.

_Initial Setup:_

1. _Launch_: Launch Notepad++ or Visual Studio Code from the Start menu or shortcut.
2. _Configure settings_: Configure the settings and preferences to your liking (e.g., font size, theme, syntax highlighting).
3. _Install extensions_: Install any additional extensions or plugins you need (e.g., language support, code completion).

4. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com*Step 1: Install Git\*

answer:

- Go to the Git download page and download the appropriate version for your operating system ,mine is windows.
- Follow the installation instructions to install Git on your computer.

_Step 2: Create a GitHub Account_

- Go to (link unavailable) and sign up for a free account.
- Enter your email address, password, and username.
- Verify your email address by clicking on the link sent to you by GitHub.

_Step 3: Configure Git_

- Open a terminal or command prompt and run the command `git config --global user.name "Your Name"` (replace "Your Name" with your actual name).
- Run the command `git config --global user.email "your_email@example.com"` (replace "your_email@example.com" with your actual email address).

_Step 4: Create a New Repository on GitHub_

- Log in to your GitHub account and click on the "+" button in the top right corner.
- Select "New repository" and enter a name and description for your repository.
- Choose the appropriate settings (e.g., public or private) and click "Create repository".

_Step 5: Initialize a Git Repository for Your Project_

- Open a terminal or command prompt and navigate to your project directory.
- Run the command `git init` to initialize a new Git repository.

_Step 6: Add Your Project Files to the Repository_

- Run the command `git add .` to stage all files in your project directory.
- Run the command `git commit -m "Initial commit"` to commit your changes with a meaningful commit message.

_Step 7: Link Your Local Repository to GitHub_

- Run the command `git remote add origin (link unavailable) (replace "your_username" and "your_repository_name" with your actual GitHub username and repository name).
- Run the command `git push -u origin master` to push your changes to the remote repository and set the upstream tracking information.

4. Install Necessary Programming Languages and Runtimes:
   Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).1. _Install Python_: pip comes bundled with Python, so install Python first (follow the steps I provided earlier).

   answer:

_Verify pip installation_: Open a terminal or command prompt and type `pip --version`. If pip is installed, this command will display the version number.

. _Upgrade pip_: If pip is already installed, you can upgrade it by running `pip install --upgrade pip`.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.Install Docker\*

8. Go to the Docker website and download
9. Follow the installation instructions to install Docker on your machine.

_Create a Docker Account_

1. Go to the Docker Hub websit and create an account.
2. Verify your email address by clicking on the link sent to you by Docker.

_Create a Dockerfile_

1. Create a new file named `Dockerfile` in your project directory.
2. Add the following code to the file:

```
FROM python:3.9-slim
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . .
CMD ["python", "(link unavailable)"]
```

This Dockerfile assumes you're using Python 3.9 and have a `requirements.txt` file in your project directory.

_Build a Docker Image_

1. Open a terminal in your project directory.
2. Run the command `docker build -t myapp .` to build a Docker image with the name `myapp`.

_Run a Docker Container_

1. Run the command `docker run -p 8000:8000 myapp` to start a Docker container from the `myapp` image.
2. The `-p 8000:8000` flag maps port 8000 on your local machine to port 8000 in the container.

_Access Your Application_

1. Open a web browser and navigate to access your document

_Virtualization Benefits_

1. Isolated dependencies: Docker ensures that your project dependencies are isolated from your system dependencies.
2. Consistent environments: Docker provides a consistent environment across different machines, ensuring that your application works as expected.
3. Easy collaboration: Docker makes it easy to share your development environment with others, ensuring that everyone is working with the same configuration.

By following these steps, you've set up a development environment using Docker, ensuring consistent and isolated dependencies across different machines.

Answer:

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Answer:

   _Visual Studio Code:_

1. _Syntax Highlighting:_ Install themes like "Material Icon Theme" or "VSCode Icons" for syntax highlighting.
1. _Code Formatting:_ Install "Beautify" or "JS-CSS-HTML Formatter" for code formatting.
1. _Version Control Integration:_ Install "GitLens" for Git integration.

_Notepad++:_

1. _Syntax Highlighting:_ Install user-defined languages like "Python" or "JavaScript" for syntax highlighting.
2. _Code Formatting:_ Install "NppFormat" for code formatting.
3. _Version Control Integration:_ Install "Notepad++ Git" for Git integration.

_Sublime Text:_

1. _Syntax Highlighting:_ Install packages like "Python" or "JavaScript" for syntax highlighting.
2. _Code Formatting:_ Install "SublimeFormatter" for code formatting.
3. _Version Control Integration:_ Install "SublimeGit" for Git integration.

_Atom:_

1. _Syntax Highlighting:_ Install packages like "language-python" or "language-javascript" for syntax highlighting.
2. _Code Formatting:_ Install "atom-beautify" for code formatting.
3. _Version Control Integration:_ Install "git-plus" for Git integration.

- IntelliJ IDEA:\*

1. _Syntax Highlighting:_ Built-in syntax highlighting for various languages.
2. _Code Formatting:_ Built-in code formatting with "Reformat Code" feature.
3. _Version Control Integration:_ Built-in Git integration with "Git" tool window.

4. Document Your Setup:
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

#Deliverables:

1. _Install Windows 11_
   - Download the Media Creation Tool
   - Create a bootable USB drive
   - Install Windows 11
2. _Install Text Editors/IDEs_
   - Notepad++: Download and install
   - Visual Studio Code: Download and install
3. _Install Version Control System_
   - Git: Download and install
   - GitHub: Create an account and set up a repository
4. _Install Programming Languages_
   - Python: Download and install
   - JavaScript: Included in Visual Studio Code
5. _Install Package Managers_
   - pip: Included in Python installation
   - conda: Download and install
6. _Configure and Customize_
   - Notepad++: Configure syntax highlighting and themes
   - Visual Studio Code: Install extensions (e.g., Python, JavaScript)
   - Git: Configure username and email
   - GitHub: Set up repository and branches
7. _Troubleshooting_
   - Resolve any installation issues or errors
   - Consult documentation and online resources as needed

_Configuration and Customizations:_

- Notepad++:
  - Syntax highlighting for Python and JavaScript
  - Theme: Dark mode
- Visual Studio Code:
  - Extensions: Python, JavaScript, Git
  - Theme: Dark mode
- Git:
  - Username and email configuration
  - Default editor: Notepad++
- GitHub:
  - Repository setup
  - Branches: Main, dev

_Troubleshooting Steps:_

- Consult official documentation for each tool
- Search online for solutions to specific issues
- Check for updates and reinstall as needed

- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:\*\*

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
