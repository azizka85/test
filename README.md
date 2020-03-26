# test
Test repository to work with git

This is my first Git project.

1) At first initialize new git repository
2) At second add new file: README.md
3) At third add this file to staging
4) At last commit all changes
5) To clone this repository to local machine, use following command:
    git clone https://github.com/azizka85/test.git test-clone
6) To add link to remote server:
    git remote add test https://github.com/azizka85/test.git
7) To push changes to the server:
    git push origin master
8) To pull request:
    git pull origin master
9) To change global configuration of git:
    git config --global user.email ...
10) To create new branch from the current branch:
    git branch ...
11) To delete branch:
    git branch -d ...


Command list with descriptions to track changes in the repository:

1) git status - status of the repository
2) git diff - show differences between repository and working directory
    a) git diff {filename} - show difference of {filename} file content between the repository and working directory
    b) git diff --staged - show differences of staged files between repository and working directory
3) git show - show information about last commit
    a) git show {change number} - show information about changes whith {change number}
4) git log - log of all changes 
    a) --oneline - short infromation of log
5) git checkout ... - checkout previous changes
    a) git checkout {change number} - checkout previous change {change number}
    b) git checkout {branch name} - switch branch {branch name}
6) git add {files} - add {files} to stage
7) git commit - commit changes
    a) git commit --amend - change description of the previous changes and commit changes
8) git revert - create new commit based on the change which checkout previously 
9) git rm --cached - remove file from staging

Gui commands:

1) To create new branch: Branch -> Create
2) To show changes: click Rescan button on bottom right box
