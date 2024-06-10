[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15240361&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration. (**PROJECT ANSWERS AT THE END OF THE PAGE**)

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11  
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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

**ANSWERS OF THE PROJECT:**

1. Install Linux
### Steps:
 1. I downloaded Ubuntu from [ubuntu.com](https://ubuntu.com/download).
 2. I created a bootable USB. -Use a tool like 'dd' command (for Linux) to create a bootable USB drive.
 3. I then installed Ubuntu following on-screen instructions.

2. ## 2. Install Visual Studio Code
### Steps:
1. I downloaded the .deb package from [Visual Studio Code](https://code.visualstudio.com/Download).
2. Opened terminal and navigated to the download location.
3. I used `sudo dpkg -i code*.deb` to install it.
4. Fix dependencies if there is any with  `sudo apt-get install -f`.

 3. Set Up Version Control System
### Steps:
1. i installed Git with `sudo apt-get install git`.
2. Configured Git with my user information. (git config --global user.name "george",
git config --global user.email "georgerubinga@gmail.com"
)
3. I createed a GitHub account and a new repository. (Sign Up:

Go to GitHub and sign up for an account if you don’t already have one.
Created a New Repository:

Loged in to GitHub.
Clicked on the New button to create a new repository.
Provided a repository name, description (optional), and choose between public or private.
)
4. Initialize a Git repository locally, add files, and push to GitHub. (1.Navigate to the project directory
2.Initialize the Git repository(git init)
3.Add files and make the first commit(git add .
git commit -m "Initial commit")
4.I linked the local repository to GitHub (git remote add origin https://github.com/george/yourrepository.git
git push -u origin master))


## 4. Install Necessary Programming Languages and Runtimes
### Steps:
1. I installed Python with `sudo apt-get install python3 python3-pip`.
2. Verify installations (python3 --version
pip3 --version)

## 5. Install Package Managers
### Steps:
 1. Verify `pip3` installation.


## 6. Configure a Database (MySQL)
### Steps:
1. I installed MySQL with `sudo apt-get install mysql-server`.
2. Secured MySQL installation (sudo mysql_secure_installation
)
3. Started MySQL service and verified (sudo systemctl start mysql).
4. Verify MySQL service status (sudo systemctl status mysql)
5. I loged in to MySQL (sudo mysql -u root -p)

## 7. Set Up Development Environments and Virtualization (Optional)
### Steps:
1. Install Docker
Docker allows you to package and run applications in isolated environments called containers.

1. Update the package list (sudo apt-get update)
2. I installed prerequisites (sudo apt-get install apt-transport-https ca-certificates curl software-properties-common)
3. Added Docker’s official GPG key (curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -)
4. Set up the stable repository (sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable")
5. I installed Docker CE (sudo apt-get update
sudo apt-get install docker-ce)
6. Verify Docker installation (sudo docker run hello-world)

## 8. Explore Extensions and Plugins
### Steps:
I installed recommended extensions in Visual Studio Code to enhance my development experience in Visual Studio Code by installing useful extensions.

1. Opened Visual Studio Code.
2. Go to the Extensions view by clicking the square icon in the sidebar or pressing Ctrl+Shift+X.
3. Searched for and installed the following extensions:
Python: Provides IntelliSense, linting, and debugging for Python.
GitLens: Enhances Git capabilities within VS Code.
Docker: Adds support for Docker containers.
Prettier - Code formatter: Ensures consistent code formatting.

## Reflection
### Challenges:

1. Dependency Issues: While installing Visual Studio Code, there were missing dependencies that needed to be resolved with sudo apt-get install -f.
2. MySQL Configuration: Securing the MySQL installation required careful attention to follow the prompts correctly.
3. GitHub Repository Setup: Ensuring the correct link between the local repository and GitHub required precise URL configuration.


**Strategies to Overcome Challenges:**
1. Research: I utilized official documentation and community forums to resolve dependency issues.
2. Step-by-Step Execution: I followed each step methodically to avoid missing any configurations, especially during MySQL setup.
3. Verification: I frequently verified installations and configurations to catch and fix issues early.
