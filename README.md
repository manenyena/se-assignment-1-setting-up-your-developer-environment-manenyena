[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15271715&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   
   •	I downloaded windows 11 which is the current release which I did an installation assistant process before



2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   •	I downloaded visual studio code and installed it following the prompts recommended 
•	After downloading I downloaded the installer and run it which along the way I had to choose the visual studio workload which I select the web development 

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   •	Installing Git and configuring it on my local machine, head to chrome search for GitHub account and create an account using my email 
•	Firstly, head to windows and type git for windows, choose the first tab and download.
•	Then we set git by following the prompts which included choosing the default editor which was notepad then next then we will click next up to the end of our setup then install.
•	Open git bash terminal then verify git version by git –version.
•	Next is to link git to GitHub by configuring it using username and email in git bash
•	Type in mkdir to make a directory and give it a name
•	Type in cd demo to change directory 
•	Then go to chrome and type in GitHub to create an account then verify your email go back to GitHub and login 
•	Create a new repository by adding the description and repository name then make it public click create repository. 
•	Go back to git bash type git status if the status cannot be shown create a new directory demo, then change directory demo
•	Then type git init then enter then check git status •	Locate your file and be inside the file the go back to terminal and type git status 
•	Then git add test.txt to add the file and track it
•	Next step is to commit by git commit –m “this is my first commit” then enter
again


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

•	I installed at python.org on windows where I chose the latest version, which was python 3.8.6, I then followed the default prompts in choosing the location then clicked on install.
•	Then I run the python on the command prompt by typing command python -version on my local machine to confirm if it was installed correctly.



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

•	I installed pip via git bash where we run the command python -m which is use to pass a massage in this case to install so all in all it is python -m pip install virtualenv.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   •	I already had MySQL, but it was lacking the correct set up and I didn’t know how to use it which caused me to not understand or follow up with the lesson and I decided to download it from scratch which meant I needed to delete the old one which I thought I did but I didn’t.
•	I then proceeded to download a new one from MYSQL community downloads which by downloading you must choose the option at the end that says ‘no thanks just start my download’ then my download started.
•	Then you locate it into your folder to see where it is located then the next step is to configure and install the will be a screen popping asking if you want it to make changes and I said yes and then I chose the option for server only and pressed next and on the next page then clicked execute.
•	Next is to configure MYSQL server on my windows where prompts such as high availability, type and networking, authentication method, accounts and roles, windows service logging options, advanced options where met.
•	Then the final step is starting MYSQL Server by entering a command in the windows command prompt.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   firstly i would choose a virtualization platform which is virtualbox then installed and downloaded it, then create a virtual machine by launching the virtualization platform athen allocate resources based on my project requirements.
   install the operating system on my windows not forgetting to ensure that it is competitable , then install dependencies, libraries and tools required for my project and use package mangers to manage dependencies .
   configure the environment and setting the PATH and others and database connect 
   clone my project into the VM using git which i prefer,test and verify the project to ensure that the dependencies are installed and configured and that it runs correctly 

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

my IDE is visual studio code so the extensions that I installed where python extension, GitHub classroom


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
