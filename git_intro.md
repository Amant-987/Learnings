# Introduction to Git

![logoGit](Git-logo.png)

## What is Git?
Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

## Preparing the repository
To create a repository, run the command **git init** in the folder with the repository and you will create a repository (a hidden .git folder will appear)

## Main command for the Git
    Before you use Git for the first time, you should introduce yourself. In the terminal, type two commands:
    1. git config --global user.name "your name on English"
    2. git config --global user.name <your email>

### *Git add*
You can use the **git add** command to add the changes to the commit. To execute this command, type **git add <file name>**

### *Checking status of the repository*
You can use the **git status** command to see the status of the repository. You can do this by typing **git status** in the repository folder and you will see whether the files have been modified or not.

### *Creating the commit*
To create the commits, run the command **git commit**. Write **git commit -m "your message "** in the terminal, and *Git* add your message to the changes you've made.

### *Checking difference*
The **git diff** command is used to calculate the difference between any two Git trees. This can be the difference between your working copy and the index (**git diff proper**), the difference between the index and the last commit (**git diff --staged**), or between any two commits (**git diff master branchB**).

### *Cancel changes* 
The command **git reset**, as you can guess from the name, is mainly used to undo changes. It changes the HEAD pointer and, optionally, the index state. It can also change files in the working directory when using the **--hard** option which can lead to loss of work if used incorrectly, so be sure to be serious before using it.

### *Deleting a Git repository*
The **git rm** command is used in Git to remove files from the index and working copy. It is similar to **git add** with the only exception that it removes rather than adds files for the next commit.

### *Move a file*
The **git mv** command is just a convenient way to move a file and then do **git add** for the new file and **git rm** for the old one.

### *Clean up "garbage"*
The **git clean** command is used to remove garbage from the working directory. This can be build results of a project or merge conflict files.