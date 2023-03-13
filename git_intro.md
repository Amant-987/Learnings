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

### *Create branch*
The **git branch <name of branch>** is a kind of "branch manager". It knows how to list your branches, create new ones, delete and rename them.

### *Merge branch*
The __git merge <name of branch to merge>__ command is used to merge one or more branches into the current branch. It then sets the pointer of the current branch to the resulting commit.

### *Git checkout*
The **git checkout <name of branch>** command is used to switch branches and upload their contents to the working directory.

### *Move a file*
The **git mv** command is just a convenient way to move a file and then do **git add** for the new file and **git rm** for the old one.

### *Clean up "garbage"*
The **git clean** command is used to remove garbage from the working directory. This can be build results of a project or merge conflict files.

Follow the links below for articles to learn more about Git:

[Git for Newbie. Part 1](https://habr.com/ru/post/541258/)

[Git for Newbie. Part 2](https://habr.com/ru/post/542616/)

[Git Commands](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9E-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B5-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D1%8F-%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D0%B9)


# Introduction for Markdown
## What is Markdown?

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004, Markdown is now one of the world’s most popular markup languages.

Using Markdown is different than using a WYSIWYG editor. In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.

For example, to denote a heading, you add a number sign before it (e.g., # Heading One). For other heading - use **##** or **###** (that would be smaller)

Or to make a phrase bold, you add two **' * '** or two **' _ '** before and after it (e.g., **this text is bold** or __this one__). It may take a while to get used to seeing Markdown syntax in your text, especially if you’re accustomed to WYSIWYG applications. The screenshot below shows a Markdown file displayed in the Visual Studio Code text editor.

## Main commands for formating

### How Creating a Table
You need to use this one '|' for columns, and this one '---' for lines. 
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### **Bold** __text__
Add two **' * '** or two **' _ '** before and after it (e.g., **this text is bold** or __this one__)

### *Italic* _text_
Add one ' * ' or ' _ ' before and after it.

### Creating Headings
Use ' # ' characters before your Headings for declaration. Two or more will make your Heading smaller in size. You can trim paragraphs in this way.











# Guten Tag, der Lehrer!