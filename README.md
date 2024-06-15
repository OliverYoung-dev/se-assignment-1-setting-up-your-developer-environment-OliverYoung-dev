[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280734&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   WHAT DO YOU NEED.



Windows installation media. This could be an installation ISO or DVD.
USB flash drive with at least 5GB free space,ensure the flash disk has nothing important since it will be formatted.
Technician PC - Windows PC that you'll use to format the USB flash drive
Destination PC - A PC that you'll install Windows on


Step 1 - Format the drive and set the primary partition as active.

Connect the USB flash drive to your technician PC.
Open Disk Management: Right-click on Start and choose Disk Management.
Format the partition: Right-click the USB drive partition and choose Format. Select the FAT32 file system to be able to boot either BIOS-based or UEFI-based PCs.
Set the partition as active: Right-click the USB drive partition and click Mark Partition as Active.


Step 2 - Copy Windows Setup to the USB flash drive.

Use File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.
Optional: add an unattend file to automate the installation process. For more information, see Automate Windows Setup.




Step 3 - Install Windows to the new PC.

Connect the USB flash drive to a new PC.
Turn on the PC and press the key that opens the boot-device selection menu for the computer, such as the Esc/F10/F12 keys. Select the option that boots the PC from the USB flash drive.
Windows Setup starts. Follow the instructions to install Windows.
Remove the USB flash drive.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
Step 1: Download Visual Studio Code
Open your web browser and go to the Visual Studio Code website:
https://code.visualstudio.com/

Click on the "Download for Windows" button:


Step 2: Run the Installer
Locate the downloaded file (VSCodeUserSetup-x64-x.x.x.exe) in your Downloads folder and double-click it to run the installer:

The Visual Studio Code Setup Wizard will appear. Click "Next" to continue:


Read and accept the license agreement, then click "Next":


Step 3: Choose Installation Location
Select the destination folder where you want to install Visual Studio Code. The default location is usually fine. Click "Next" to proceed:

Step 4: Select Additional Tasks
Choose any additional tasks you want to perform. It's recommended to check the following options for better usability:
Add "Open with Code" action to Windows Explorer file context menu
Add "Open with Code" action to Windows Explorer directory context menu
Register Code as an editor for supported file types
Add to PATH (important for using the code command in the terminal)
Click "Next" after selecting the desired options.

Step 5: Install Visual Studio Code
Click the "Install" button to begin the installation:


The installation process will start. Wait for it to complete:


Step 6: Launch Visual Studio Code
Once the installation is complete, make sure the "Launch Visual Studio Code" checkbox is checked, then click "Finish":

Step 7: Open Visual Studio Code
Visual Studio Code will open. You can start using it to edit your code:

Step 8: Verify code Command (Optional)
To verify that the code command works, open a Command Prompt or PowerShell window and type code. This should open Visual Studio Code.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Step 1: Download Git
Open your web browser and go to the Git website:
https://git-scm.com/

Click on the "Download" button for Windows:

Step 2: Run the Installer
Locate the downloaded file (Git-x.x.x-x64.exe) in your Downloads folder and double-click it to run the installer:

The Git Setup Wizard will appear. Click "Next" to continue:

Step 3: Select Installation Location
Select the destination folder where you want to install Git. The default location is usually fine. Click "Next" to proceed:
Step 4: Select Components
Select the components you want to install. It's recommended to leave the default options checked. Click "Next" to continue:
Step 5: Select Start Menu Folder
Choose the start menu folder where you want to create the Git shortcuts. The default is usually fine. Click "Next" to proceed:
Step 6: Adjusting PATH Environment
Select the option "Git from the command line and also from 3rd-party software". This will allow you to use Git from the command line and other applications. Click "Next" to continue:
Step 7: Choosing HTTPS Transport Backend
Choose the "Use the OpenSSL library" option for HTTPS connections. Click "Next" to continue:
Step 8: Configuring Line Ending Conversions
Select "Checkout Windows-style, commit Unix-style line endings" for the line ending conversions. Click "Next" to proceed:
Step 9: Configuring Terminal Emulator
Choose "Use MinTTY (the default terminal of MSYS2)" for the terminal emulator. Click "Next" to continue:
Step 10: Extra Options
Leave the default options checked for extra features. Click "Next" to proceed:
Step 11: Completing the Installation
Click "Install" to begin the installation process. Wait for it to complete:

Once the installation is complete, you can choose to launch Git Bash or view the release notes. Click "Finish" to exit the installer:

Step 12: Configure Git
Open Git Bash by searching for it in the Start menu:

Configure your username and email address for Git by running the following commands in Git Bash:
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Installation on Windows
Visit the link https://www.python.org/downloads/

to download the latest release ofPython. In this process, we will install Python 3.8.6 on ourWindows operating system. When we click on the above link, it will bring us the following page.

Step - 1: Select the Python's version to download.
Step - 2: Click on the Install Now

Double-click the executable file, which is downloaded;

the following window will open.

Select Customize installation and proceed.

Click on the Add Path check box, it will set the Python path automatically.
We can also click on the customize installation to choose desired location and features. Other important thing is install launcher for the all user must be checked.

Step - 3 Installation in Process
Now, try to run python on the command prompt. Type the command python -version in case of python3


5. Install Package Managers:
   If applicable, install package managers like pip (Python).


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

  Step 1: Download MySQL
Open your web browser and go to the MySQL official website:
https://dev.mysql.com/downloads/installer/

Click on "MySQL Installer for Windows":

Choose the appropriate installer (either the web community installer or the full installer) and click "Download":

Step 2: Run the Installer
Locate the downloaded file (mysql-installer-web-community-x.x.x.x.msi or mysql-installer-community-x.x.x.x.msi) in your Downloads folder and double-click it to run the installer:

The MySQL Installer will appear. Click "Next" to continue:

Step 3: Choose Setup Type
Select a setup type. For most users, "Developer Default" is recommended as it includes the MySQL Server, MySQL Workbench, and other development tools. Click "Next" to continue:
Step 4: Check Requirements
The installer will check for any requirements and dependencies. If any are missing, it will prompt you to install them. Click "Execute" to install any required components:
Step 5: Installation
After the requirements are installed, the installer will list the MySQL products to be installed. Click "Execute" to start the installation:

Wait for the installation to complete. Once finished, click "Next" to proceed:

Step 6: Configuration
The MySQL Server Configuration screen will appear. Click "Next" to start the configuration process:
Step 7: Configure MySQL Server
Choose the "Standalone MySQL Server / Classic MySQL Replication" option and click "Next":

Set the Type and Networking options. The default settings are usually fine. Ensure the port number is set to 3306. Click "Next":

Set the authentication method. Choose "Use Strong Password Encryption for Authentication (RECOMMENDED)" and click "Next":

Set the MySQL Root Password and create a new user (optional). Click "Next" after setting the password:

Configure the Windows Service settings. Ensure "Configure MySQL Server as a Windows Service" is checked. Click "Next":

Step 8: Apply Configuration
Click "Execute" to apply the configuration settings:

Wait for the configuration to complete, then click "Finish":

Step 9: Complete Installation
Click "Next" to proceed to the final steps of the installation:

Click "Finish" to complete the installation:

Step 10: Open MySQL Workbench
Open MySQL Workbench by searching for it in the Start menu:

Click on the "Local instance MySQL" to open a connection to your local MySQL server. Enter the root password you set during the configuration and click "OK":

Step 11: Verify Installation
You can now use MySQL Workbench to manage your databases. To create a new database, click on the "Create a new schema" button:

Enter a name for your new schema and click "Apply":

Review the SQL script and click "Apply" again to create the schema:

Your new database schema should now be created and visible in the Schemas panel:
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Step 1: Install Docker Desktop for Windows
Open your web browser and go to the Docker Desktop website:
https://www.docker.com/products/docker-desktop/

Click on "Download Docker Desktop for Windows":

Save the installer file and locate it in your Downloads folder:

Step 2: Run the Docker Desktop Installer
Double-click the downloaded installer file (Docker Desktop Installer.exe) to run it:

Follow the on-screen instructions in the Docker Desktop setup wizard. Check the "Install required components for WSL 2" checkbox and click "OK" to continue:

Step 3: Configure Docker Desktop
Once the installation is complete, Docker Desktop will launch. You will be prompted to log in to your Docker account. If you don't have an account, you can create one for free:

After logging in, Docker Desktop will start. You may need to enable WSL 2 if it's not already enabled. Docker Desktop will prompt you to enable it if necessary:
8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Syntax Highlighting and Language Support
Programming Language Extensions

Install extensions specific to your programming languages (e.g., Python, JavaScript, Java, etc.) for enhanced syntax highlighting, code snippets, and language-specific features.
Example Extensions:

Python: Python (by Microsoft), Python Extension Pack
JavaScript/TypeScript: JavaScript (ES6) code snippets, TypeScript Hero
Java: Java Extension Pack, Language Support for Java(TM) by Red Hat
Linting and Code Quality
Linting Extensions

Ensure code quality with linting tools that detect errors, potential bugs, and style issues.
Example Extensions:

ESLint, Pylint, TSLint, PHP Intelephense
Code Formatting
Formatting Extensions

Automatically format your code according to predefined or customizable rules.
Example Extensions:

Prettier - Code formatter, Beautify, PHP Intelephense
Version Control Integration
Git Extensions

Enhance Git integration with features like status indicators, diff viewers, and branch management.
Example Extensions:

GitLens - Git supercharged, GitHub Pull Requests and Issues, Git History
Productivity Tools
Code Snippets and Templates

Speed up coding with predefined code snippets and templates for common tasks.
Example Extensions:

Code Spell Checker, TODO Highlight, Bracket Pair Colorizer
Development Environment Enhancements
Debugger and Runtime Extensions

Debug your code effectively with debugger extensions for different languages and runtimes.
Example Extensions:

Debugger for Chrome, PHP Debug, Java Debugger for Visual Studio Code
Popular Extension Packs
Extension Packs

Bundles of related extensions that provide a set of tools for specific development environments or languages.
Example Packs:

Python Extension Pack, JavaScript (ES6) code snippets, Docker, Kubernetes
Installing Extensions in VS Code
Accessing Extensions

Open VS Code, go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side or by pressing Ctrl+Shift+X.
Search and Install

Search for extensions by name or category in the Extensions Marketplace.
Click "Install" next to an extension to install it.
Some extensions may require additional setup or configuration; follow their documentation for guidance.
Example Workflow
Setting Up for JavaScript Development:

Install extensions like "JavaScript (ES6) code snippets" for quick code generation.
Use ESLint for linting and Prettier for code formatting to maintain code quality and consistency.
Integrate GitLens for enhanced version control management directly within VS Code.
Python Development Environment:

Install Python extension pack for comprehensive support, including linting with Pylint and formatting with Prettier.
Use Git integration tools like GitHub Pull Requests and Issues for collaborative development.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Step 1: Install Visual Studio Code
Download Visual Studio Code:

Open your web browser and navigate to https://code.visualstudio.com/.
Click on "Download for Windows" and save the installer file.
Run the Installer:

Locate the downloaded file (VSCodeUserSetup-x64-x.x.x.exe) in your Downloads folder and double-click it.
Follow the on-screen instructions to complete the installation.
Launch Visual Studio Code after installation.
Step 2: Configure Visual Studio Code
Install Essential Extensions:

Open Visual Studio Code.
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side or by pressing Ctrl+Shift+X.
Search for and install the following extensions:
Language-specific extensions (e.g., Python, JavaScript).
Code formatting extensions (e.g., Prettier).
Git integration extensions (e.g., GitLens).
Optional: Docker extension for Docker integration.
Click on "Install" for each extension.
Configure Settings:

Click on the gear icon (Settings) in the lower-left corner or press Ctrl+, to open User Settings.
Modify settings according to your preferences, such as font size, theme (Color Theme), and default language.
Consider enabling "editor.formatOnSave": true for automatic code formatting on save.
Step 3: Setting Up Version Control (Git)
Install Git:

Download Git for Windows from https://git-scm.com/download/win.
Run the installer and follow the on-screen instructions.
Open a Command Prompt or PowerShell window and verify the installation by typing git --version.
Configure Git:

Set your username and email for Git
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
Verify your Git configuration
   git config --global --list
Step 4: Install Additional Tools (Optional)
Install Node.js and npm:

Download Node.js installer from https://nodejs.org/ and run it.
npm (Node Package Manager) is included with Node.js.
Install Docker (Optional):

Download Docker Desktop for Windows from https://www.docker.com/products/docker-desktop.
Run the installer and follow the on-screen instructions.
Enable WSL 2 if prompted during installation for better performance.
Step 5: Create and Manage Projects
Create a New Project:

Open Visual Studio Code.
Use Ctrl+Shift+N to create a new folder and open it in VS Code.
Start coding by creating new files or editing existing ones.
Version Control with Git:

Initialize a Git repository in your project folder
cd /path/to/your/project
git init
Stage and commit changes using VS Code’s Source Control view or Git commands in the terminal.
Troubleshooting Tips
Extensions Not Working: Disable conflicting extensions or update them to the latest version.
Visual Studio Code Performance: Close unnecessary tabs and consider limiting the number of active extensions.
Git Authentication Issues: Ensure correct credentials are configured and permissions are set on remote repositories.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
