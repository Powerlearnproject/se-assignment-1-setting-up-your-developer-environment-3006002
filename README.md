[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15327868&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:
# Visual Studio
To install Visual Studio, begin by downloading the installer from the official Visual Studio website and running it. During installation, select specific workloads such as .NET desktop development or Python, and optionally customize with individual components or language packs. Once chosen, initiate the installation process and wait for it to complete, ensuring a stable internet connection. After installation, launch Visual Studio from the Start menu or desktop shortcut, optionally sign in with your Microsoft account for added features, and configure preferences on first launch. Keep Visual Studio updated through the menu to access the latest features and begin coding with confidence using its extensive development tools and resources
# Installing Git, Creating Github account and repository
To begin, install Git by downloading it from git-scm.com/download and following the installation instructions. After installation, open a command prompt or terminal to configure Git with your username and email using git config --global user.name "Your Name" and git config --global user.email "your@email.com". Next, create a GitHub account at github.com if you haven't already. Once logged in, click on the "+" sign at the top right of the page, select "New repository," and name it with an optional description. Choose whether it should be public or private, then click "Create repository." To push your code to this repository, initialize a Git repository locally with git init, add your files with git add ., commit them using git commit -m "Initial commit", add the remote repository URL with git remote add origin https://github.com/your-username/your-repo-name.git, and finally push your changes to GitHub with git push -u origin master, entering your GitHub credentials if prompted. This process establishes Git for version control and GitHub for repository hosting, facilitating collaboration and code management. Adjust commands as necessary for SSH authentication or repository specifics.

# Python instllation
To install Python, visit the official Python website at python.org and download the appropriate installer for your operating system (Windows, macOS, or Linux). Run the installer by double-clicking the downloaded file and follow the prompts to customize your installation. Make sure to select the option to "Add Python to PATH" during installation for easier command line access. After installation, verify Python is correctly installed by opening a command prompt or terminal and typing python --version. This command should display the installed Python version. Optionally, check if pip, Python's package manager, is installed by typing pip --version and install it if necessary following Python's documentation. With Python installed and verified, you can start coding in Python for various applications like scripting, web development, and data analysis by launching the Python interpreter with the python command in your terminal or command prompt
# Installation of MySQL
To install MySQL database on your system, begin by visiting the MySQL download page at dev.mysql.com/downloads. Choose the appropriate installer for your operating system (Windows, macOS, or Linux) and download it. Run the downloaded installer and follow the on-screen instructions. During installation, select the "Custom" option to customize the installation type. Choose components such as MySQL Server and MySQL Workbench. Set the installation directory and configure options like the default storage engine (e.g., InnoDB). Create a root password when prompted, which you'll use to access MySQL. Complete the installation process and launch MySQL Workbench or use the command line to verify the installation. Connect to MySQL, create databases, and manage users as needed for your projects. Adjust configurations based on specific requirements or system preferences to ensure MySQL is properly installed and configured for your development environment.

# Set Up Development Environments and Virtualization (Optional): 
Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
I am running windows 11 and as a result will not require the use of a virtual macine.

# Explore Extensions and Plugins: 
Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Exploring Extensions, Plugins, and Add-Ons for Visual Studio
Step 1: Access the Visual Studio Marketplace
Open Visual Studio. Click on the "Extensions" tab in the top menu. This will open the Visual Studio Marketplace. Step 2: Browse Extensions
Use the search bar to find specific extensions or browse by category. Some popular categories include: Code Editing Debugging Tools Productivity Tools Version Control Step 3: Explore Extension Details
Click on an extension to view its details. Read the description, features, and user reviews. Check the compatibility with your Visual Studio version and project type. Step 4: Install Extensions
Click on the "Download" button to install the extension. Depending on the extension, you may need to restart Visual Studio for the installation to take effect. Step 5: Examples of Useful Extensions

# Syntax Highlighting and Linting
Roslynator - Enables rich syntax highlighting and semantic analysis for C# and Visual Basic. EditorConfig for Visual Studio - Enforces coding standards and conventions across team members. Code Formatting
Prettier - Automatically formats JavaScript, JSON, and TypeScript code according to a consistent style. CodeMaid - Provides code cleanup, formatting, and refactoring tools. Version Control Integration
Git - Integrates Git version control functionality within Visual Studio. Azure DevOps - Connects Visual Studio to Azure DevOps for project tracking and collaboration. Additional Tips
Use filters to narrow down search results based on language, category, or feature. Read user reviews and ratings to assess the quality of extensions. Keep your extensions up-to-date to ensure compatibility and bug fixes. Use the "Manage Extensions" window to enable, disable, or uninstall extensions. Consider using an extension manager like Extensis for easier management and updates.

 
