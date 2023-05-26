
## Lab: work with git and git commands
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Part 1: Configurating Git User Profile

To setup the project for the first time, please follow below steps:

##### 1.1.  Verify git installation
use below command to verify the git installation (ignore the leading double slashes, and do the same for all the rest commands in this lab)
   ```sh
   git version
   ```
##### 1.1. Configure local git global user profile
use below commands to configure the git user profile. Replace the text within the arrow bracket (including the arrows) with your personal inputs ###
   ```sh
    git config --global user.name <your-name>
    git config --global user.email <your-email>
   ```


### Part 2: Initialise a new local git repo

##### 2.1.  Create a root directory for local git repositories
Within your personal drive, at the root level, create a new folder called 'repos'. 
For example, if your personal drive is D:/ drive, create a 'repos' folder and the final directory for the folder is D:/repos

##### 2.2.  Open a new commmand prompt window (For Mac and Linux user, terminal window).
Navigate to the directory as per created above. For example, for Windows User, use below commands in the command prompt and hit enter to navigate to D:/repos
   ```sh
    D:/repos
   ```

##### 2.3.  Create a new project folder within the repos
User below command to create a new directory for the lab content, and navigate to this newly created directory:
  ```sh
   mkdir lab-git-commands
   cd lab-git-commands
  ```

##### 2.4.  Observe your directory location and confirm you're currently landing at <drive>:/repos/lab-git-commands
Use below commands to initialise a new local git repo, and observe the message returned in the console:
  ```sh
   git init
  ```


<p align="right">(<a href="#readme-top">back to top</a>)</p>


