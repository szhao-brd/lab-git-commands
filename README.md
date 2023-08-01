
## Lab: work with git and git commands
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Part 1: Configurating Git User Profile

To setup the project for the first time, please follow below steps:

1. ##### Verify git installation
 ###### use below command to verify the git installation (ignore the leading double slashes, and do the same for all the rest commands in this lab)
   ```sh
   git version
   ```
##### 1.1. Configure local git global user profile
use below commands to configure the git user profile. Replace the text within the arrow bracket (including the arrows) with your personal inputs ###
   ```sh
    git config --global user.name <your-name>
    git config --global user.email <your-email>
   ```
 <br /> <br />

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

##### 2.4. Init a new Git repo
Observe your directory location and confirm you're currently landing at <drive>:/repos/lab-git-commands
Use below commands to initialise a new local git repo, and observe the message returned in the console:
  ```sh
   git init
  ```
 <br /> <br />

### Part 3: Adding Git Commits
##### 3.1.  Make some changes
Copy the index.html and the index.js files from the downloaded folder, and paste them into the root directory of your project folder.  <br />
Once the pasting is complete, open a new command prompt, and within it, use the command line shown below to navigate to your project folder root:
  ```sh
   cd <drive>:/repos/lab-git-commands
  ```

##### 3.2.  Stash changes
\*note: the git stached changes is a temp space where git manages the temporary memory of point-in-time changes. All changes need to be stached first, before they can be committed to the git history. 
  ```sh
   git add --all
  ```
   
##### 3.3.  Commit changes
Use the command at the bottom of this section to COMMIT all the new changes.  <br />
A git commit message editor will automatcially prompt out and ask for a commit message. Please enter 'lab commit' in the blank line, as the commit message content. <br />
After that, hit the 'ESC' key on your keyboard, and in the new blank line, type ':wq' and hit 'Enter' key to save the message. <br />
Git will commit the changes once the message is saved successfully.

  ```sh
   git commit
  ```

##### 3.4. Congratulations! You have just successfully initialised a new git repo, and committed the first changes into this repos's git history.


   
<p align="right">(<a href="#readme-top">back to top</a>)</p>


