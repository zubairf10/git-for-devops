
### Directory and File Operations

```bash
mkdir git-for-devops
```
Creates a directory named `git-for-devops`.

```bash
cd git-for-devops
```
Navigates into the `git-for-devops` directory.

```bash
pwd
```
Prints the current working directory.

```bash
ls -a
```
Lists all files, including hidden ones, in the current directory.

```bash
ls
```
Lists the files and directories in the current directory.

```bash
clear
```
Clears the terminal screen.

```bash
touch nibba.txt nibbi.txt
```
Creates two new empty files, `nibba.txt` and `nibbi.txt`.

```bash
rm hello.txt
```
Removes the file `hello.txt`.

```bash
git status
```
Displays the current state of the Git repository, showing changes to be committed, changes not staged for commit, etc.

```bash
git restore nibbi.txt
```
Restores the `nibbi.txt` file to its previous state (removes uncommitted changes).

### Git Initialization and Configuration

```bash
git init
```
Initializes a new Git repository in the current directory.

```bash
git config --global user.name "zubairf10"
```
Sets the global Git username.

```bash
git config --global user.email "zubairfarooqui1850@gmail.com"
```
Sets the global Git email.

### Git Commit and Status

```bash
git add nibba.txt
```
Stages the `nibba.txt` file for commit.

```bash
git commit -m "added to tracked stage"
```
Commits the staged changes with the message "added to tracked stage".

```bash
git commit -m "made changes to nibba"
```
Commits changes made to `nibba.txt` with the message "made changes to nibba".

```bash
git add nibba.txt
```
Stages `nibba.txt` for the next commit.

```bash
git log
```
Shows the commit history.

```bash
git log --oneline
```
Displays the commit history in a condensed, one-line format.

### Branching Operations

```bash
git branch -b dev
```
Creates and checks out a new branch named `dev`.

```bash
git checkout -b dev
```
Creates and switches to a new branch `dev`.

```bash
git branch
```
Lists all Git branches.

```bash
git checkout master
```
Switches to the `master` branch.

```bash
git checkout dev
```
Switches to the `dev` branch.

```bash
git switch master
```
Switches to the `master` branch using the `git switch` command (alternative to `git checkout`).

### File Editing and Git Commit in Dev Branch

```bash
vim nibba.txt
```
Opens the `nibba.txt` file in the `vim` editor.

```bash
git add nibbu.txt
```
Stages `nibbu.txt` for commit.

```bash
git commit -m "nibbu added to dev"
```
Commits the addition of `nibbu.txt` to the `dev` branch.
