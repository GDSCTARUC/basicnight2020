# DSC Basic Night (Git Session)

### Git Configuration

###### Configuration on name and email

`git config --global user.name "<name>" `

`git config --global user.email <email>`

###### Configuration on carriage return / line feeding conversion

`git config --global core.autocrlf false`

###### Configuration on editor

`git config --global core.editor "<editor name>"`

> **_NOTE:_** If you are using other editor than vim and nano, you should put --wait parameter after the name of the editor you passed in. `git config --global core.editor "atom --wait"`

---

### Git  Basics

`git init` - Initialize the folder to let git know this is a local repository

`git add` - Add files to staging area

`git status` - View the state of the staging area

> `-s` - Show status concisely

`git commit` - Commit files to the repository

> `-m` - commit message

`gir branch` - Create branch separately with master branch

---

### View Commit History

`git log` - Review and read the history of commits 

> `--oneline` - Show the short version of the commit history
>
> `--reverse` - Reverse the order of the commit history

`git show` - Show textual difference and various types of object

`git ls-tree` - Lists the contents of a given tree object

`git restore` - Can be used to remove files from the staging area or restore files from previous commit history

> _**NOTE**_: If you do not want to copy the hexadecimal of each commit, you can use **HEAD** instead.
>
> If you want to use the commit **n** step before the latest commit, you can do **HEAD~n**
>
> **n** denotes 1,2,3...

---

### Remote Repository 

`git push` - Push files from local repository to remote repository

`git pull` - Fetch and download the content from remote repository

`git clone` - Clone repository

---

# Linux Commands that used in the session

`cd` - Change directory

`ls` - List all the files in a directory

`mkdir` - Create a directory

`touch` - Create a file

`pwd` - show current directory path





