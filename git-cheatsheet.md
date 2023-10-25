# Git Stylesheet

`git status` List all files that have changed and their state
`git add <filename>` / `git add .` Add a file to the stage / Add all files to the stage
`git commit -m "commit message"` Create a commit inluding all staged files
`git log --online` Show the commit history
`git push` Upload content to the remote repository
`git pull` Download content from the remote repository
`git clone` Creates a clone of the remote repository on the local machine
`git restore` Restores individuel files

`code .` Opens repository in vs.code

`git switch -c <branchname>` reate new branch and switch to it
`git switch <branchname>` switch branches
`git branch` list your branches
`git branch -a` list all branches (local and remote)
`git branch -d <branchname>` delete branch

## Right oder

### Once per Project

1.  `git init` create a repository.
    Don't forget to add a .gitignore file
2.  `git remote add origin <ssh-path-to-github>`

### For each Feature

1. `git switch -c <branchname>` create and switch to a new branch
2. `git add <file>` / `git add .` add a file to the stage / add all files to the stage
3. `git status` check, if everthing is ok
4. `git commit -m "commit message"` commit the changes / the file is saved in git
5. `git push -u origin <branchname>` push to GitHub
6. Continue on GitHub

### On GitHub

- Create a pull request for that branch (to merge it into main)
- Send a link to the changed files to your team
- Get a code review
- Optional: implement changes, push again to update pull request
- Merge and delete the branch on GitHub
- Continue in the shell

### In the SHELL

1.  `git switch main`
2.  `git pull` get the merged commits in your local main
3.  `git branch -d <oldbranchname>` delete the merged branch

## Terminal Stylesheet

`ls` list the content of the current directory
`cd <foldername>` change directory into a folder
`cd ..` / `cd ../../` change into a parent folder / more steps
`cd ~` change into your home directory
`pwd` print the current directory path
`touch example.md` create a new file called "example.md"
`mkdir newFolder` create a new folder called "newFolder"
`mv <old name> <new name>` move or rename a file
`rm <filename>` delete a file permanently (there is no trash bin to recover files)
`open .` open the current folder in the finder
`cat <filename>` prints the content of a specific file
`curl <ul>` prints the received content from the specified url
