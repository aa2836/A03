# A03 
Git/GitHub and Webstrom Tutorial:
1. Download Webstrom from https://www.jetbrains.com/student/
2. Install Git as a local program from https://git-scm.com/downloads
3. Create a GitHub account on https://github.com/join
4. Connect Github with Webstorm
   • In Webstorm press (Ctrl+Alt+S) for system preferences.
   • Select Version control Git. Enter the path to the git.exe
5. Add Github Password to Webstorm
   • In Webstorm press (Ctrl+Alt+S) for system preferences
   • Select Appearance and Behavior | System Settings | Passwords
6. Create a Repository
   • Click the + sign in the upper right corner
   • Choose “Create New repository”
7. The Repository is Set-up
   10
   Make the repository public and add the readme file.
   Click Create
8. Create a Repository from Webstorm
   • Select VCS and Import into Version Control
9. Import a Repository from Github
   12
   • From Main page Select Checkout from version control Git  OR
   From within Webstorm Select VCS  Checkout from version control Git
   • Enter Github repository name
   • Enter local path name
10. Creating a Webstorm File
    13
    • Choose File  HTMLHTML 5 or FileStylesheet
11. Add files to Git
    14
    The Add to Git dialog opens.
    Click Add. This adds to local file system
12. Commit Your Changes
13. Push Change to Remote Repository
    16
    Click “Ctrl Shift  K”
    Or “VCS  Git  Push”
14. File is now on Github
15. Set up Github Pages
    18
    Click Settings
    Check the repository name
16. Choose GitHub Page Location
    19
    Select “Master branch”
    Note the published URL
17. Check your GitHub Pages
    20
    Copy the Github.io URL into a browser
    Post the URL into Moodle with your Github account URL

Terms and Definition:

+ **Branch** A branch represents an independent line of development. Branches serve as an abstraction for the edit/stage/commit process. You can think of them as a way to request a brand new working directory, staging area, and project history.
+ **Clone** A clone is a copy of a repository or the action of copying a repository. When cloning a repository into another branch, the new branch becomes a remote-tracking branch that can talk upstream to its origin branch
+ **Commit** A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
+ **Fetch** When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch
+ **GIT** Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
+ **GitHUb** GitHub provide a service to an entire organization and use their own identity when performing their function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.
+ **Merge** Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
+ **Merge Conflict** A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
+ **Push** To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
+ **Pull** Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
+ **Remote** This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
+ **Repository** A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.


Reference:

1. “How to Use Git {Beginner's Guide} + Getting Started with Github.” Knowledge Base by PhoenixNAP, 17 Aug. 2022, 
    https://phoenixnap.com/kb/how-to-use-git. 

2. Jetbrains. (2019). Git.   Retrieved March 21, 2019, from
   https://www.jetbrains.com/help/webstorm/using-git-
   integration.html
3. GitHub (2019) GitHub Guides Tutorial. Retrieved  March
   19, 2019, from
   https://guides.github.com/activities/hello-world/

