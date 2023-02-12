# Linux-Git-GitHubActions
Contains some useful information about the commands of Linux, Git and GitHub Actions. 
<br>
## Git
<br>
** Introduction **
<br>
Git is a free and open-source version control system. Git was created by Linus Torvalds in 2005 as a way to manage the development of the Linux kernel.<br>
It is now used by millions of developers and organizations around the world to track and manage their projects. Git is a distributed version control system, <br> 
meaning that each developer has a copy of the full repository on their own system. This allows them to work independently, making commits, branching, and merging <br>
without having to coordinate with each other. It helps in collaboration on projects by enabling multiple users to work on the same code base in a secure, distributed manner.
<br>
** Useful Commands ** <br>

### git init: <br>
This command is used to initialize a new Git repository in the current directory.<br>

### git clone: <br>
This command is used to clone a repository from a remote source onto your local machine.<br>

### git add: <br>
This command is used to stage changes in the working directory to be committed.<br>

### git commit: <br>
This command is used to save changes to the local repository. It is recommended to always include a descriptive message with your commit. <br>

### git status: <br>
This command is used to check the status of the repository, including the current branch, staged changes, and any uncommitted changes.<br>

### git push: <br>
This command is used to upload changes from the local repository to a remote repository, such as GitHub. <br>

### git pull: <br>
This command is used to download changes from a remote repository to the local repository.<br>

### git branch: <br>
This command is used to manage branches in the repository. You can use it to list existing branches, create new branches, or switch between branches.<br>

### git checkout: <br>
This command is used to switch between branches or checkout a specific version of a file.<br>

### git merge: <br>
This command is used to combine changes from multiple branches into a single branch.<br>
<br>
<br>


## Linux <br>
Linux is an open-source operating system that is used in a variety of digital devices such as computers, servers, and smartphones. It is based on the Unix kernel and is distributed under the GNU General Public License.<br>
It is highly customizable, allowing users to modify the system based on their needs. It is also free and open-source, meaning anyone can access, modify and redistribute its source code.<br>
Linux is popular due to its stability and reliability, as well as its wide range of applications, tools, and utilities.
<br>
** Useful Commands **
<br>
<br>
Linux has a variety of commands that allow users to access and manipulate files, directories, and other system features. 

### ls <br>
'ls' which lists the contents of a directory.<br>
### cd <br>
'cd' which allows users to change directory.<br>
### pwd <br>
'pwd' which prints the current working directory.<br>
### mkdir <br>
'mkdir' which creates a new directory.<br>
### cp <br>
'cp' which copies files.<br>
### mv <br>
'mv' which moves and renames files.
### rm <br>
'rm' which removes files.<br>
### chmod <br>
'chmod' which changes the access permissions of a file.<br> 

## GitHub Actions <br>
GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline. <br>

** Useful Commands **
<br>
<br>
### Checkout <br>
It is used to clone a repository onto a runner and make it available to run commands against it. It takes two arguments, the repository URL (either ssh or https) and the version/commit to checkout.<br>
### Actions/upload-artifacts <br>
The 'actions/upload-artifact' command is used to upload an artifact from the runner to the repository. It takes two arguments, the first is the name of the artifact, and the second is the file path to upload.<br>
### Actions/download-artifact <br>
The 'actions/download-artifact' command is used to download an artifact from the repository to the runner. It takes two arguments, the first is the name of the artifact, and the second is the local file path that the artifact should be downloaded to. <br>
### Runs <br>
The 'runs' command is used to trigger a workflow to run. It takes two arguments, the first is the name of the workflow and the second is the event name. <br>
### Actions/cache <br>
The 'actions/cache' command is used to persist data between runs of a workflow. It takes two arguments, the first is the path of the directory or file to cache and the second is an optional key. <br>

