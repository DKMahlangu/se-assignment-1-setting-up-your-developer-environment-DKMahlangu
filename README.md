# Assignment: Setting Up Your Developer Environment

**1. Select Your Operating System (OS):**
   I am using an entry level laptop therefore Windows 10 is prefereble for my laptop. You can Download and Install Windows here:       
   (https://www.microsoft.com/software-download/)

**2. Install a Text Editor or Integrated Development Environment (IDE):**
   I chose Visual Studio Code for my IDE because it supprts a wide range of programming languages and frameworks and it's also easy          to navigate and use. Download and Install Visual Studio Code (https://code.visualstudio.com/Download)

**3. Set Up Version Control System:**
   I had already created a GitHub account for hosting my projects before starting the programme and installed git and GitHub desktop         which i find easy to use unlike having to create the repository, commit and push it on GitBash.
   To install Git go to (https://git-scm.com/download/win) and follow installation instructions.
   To download and install GitHub Desktop go to (https://desktop.github.com) and follow instructions.

After installing Git, you need to configure your user information and some default settings. Open a terminal (Command Prompt or GitBash on your computer/ laptop).

> Configuring Git:      
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"

To verify the confiiguration: 
   git config --list

> Creating a GitHub Account:
    Go to (https://github.com) and follow instructions.

> Initialize a Git Repository:
   Navigate to your project directory:
      mkdir myproject
      cd myproject

> Initialize a new Git repository:
    git init

> Create a new file:
   echo "# My Project" > README.md

> Add files to the staging area:
   git add README.md
or add all files:
   git add .

> Commit the files:
   git commit -m "Initial commit"

> Link to the remote repository:
   git remote add origin git@github.com:yourusername/your-repository.git

> Push to the remote repository:
   git push -u origin master

**5. Install Necessary Programming Languages and Runtimes:**
   I installed Python from (http://wwww.python.org) and followed installation instructions and also made sure to check the option to add     Python to your PATH.

**6. Install Package Managers:**
from Command prompt
 #Verify pip installation:
    pip --version
   
 #Install or upgrade pip:
    python -m pip install --upgrade pip.

**8. Configure a Database (MySQL):**
   I Downloaded and installed MySQL from (https://dev.mysql.com/downloads/windows/installer/5.7.html) and also downloaded mySQL              workbench.

**9. Set Up Development Environments and Virtualization (Optional):**
   I have not yet installed Virtualization tool as i have not yet need them, will download them when i need them for use.

**10. Explore Extensions and Plugins:**
   These are the extensions i installed on my VS Code:
      -Code Runner
      -Data Wrangler
      -Prettier
      -GitHub pull Requests
      -Live Preview
      -Live Server
      -Live Share
      -Matplotlib
      -Pylance
      -Python
      -Python Debugger
      -Python Image Preview
      -GitLens
      -Error Lens
   
