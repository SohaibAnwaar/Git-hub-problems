Git Commands
============

## Translated Versions
- [Versão em português](READMEpt.md)

___

_A list of my commonly used Git commands_

*If you are interested in my Git aliases, have a look at my `.bash_profile`, found here: https://github.com/joshnh/bash_profile/blob/master/.bash_profile*

--

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git diff [source branch] [target branch]` | Preview changes before merging |





# Problem Git hub -permission denied Solution

# Solution : 

you have to add you ssh key in your git-hub profile. Follow steps to solve this problem

1. Right Click Folder you want to push in git
2. Select git-bash here problem
3. Write command ssh-keygen by this command your key is generated
4. Copy the key from cmd or go to (C:/User/your_user/.ssh/)
5. open id.rsa with notepad.
6. Copy your key
7. Now go to your git-hub profile
8. Go to settings
9. select **SSH and Gpg keys** 
10. select **New ssh key** option
11. add **window-key** in the title 
12. Paste your key in the description part below title field
13. Save

Now you are ready to push your folder

1. Now go to folder you want to upload
2. right click on the folder
3. Select git bash here 
4. git init
5. git add README.md
6. git commit -m "first commit"
7. git remote add origin https://github.com/<UserName>/<repo.git>
8. git push -u origin master

Hope this will be Helpful for you


# For Upload code into the new branch follow this.
1. Go to folder which you want to upload (already exists in github)
2. Right click select git bash

write command
Go to folder which you want to upload (already exists in github)
Right click select git bash
write command


Merge your things
You new brach is created
1. git init
2. $ git branch <branch_name>
$ git checkout <branch_name> 
3 git push -u origin <branch_name>
4. Now go to pull-request option in github 
5. Comapare new branch with previous branch 
6. Solve Conflicts 
7. Merge your things
8. You new brach is created

