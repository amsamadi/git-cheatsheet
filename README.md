# git-cheatsheet
### Git cheat sheet that serves as a quick reference for basic Git commands to help you learn Git

#### This document contains some common questions and their answers about git  
---
# Questions:
## 1- Why we use version control system? 
* In order to centrally and seamlessly management of software source code. Version control systems are software tools that help software teams manage changes to source code over time 
---
## 2- What is repository?  What important files does a good repository have?
* Repositories in GIT contain a collection of files, branches, tags, releases and so on of various different versions of a Project. A good repository includes LICENSE, README and .gitignore files
---
## 3- What are the parts of a good document?
* What does it do and how does it work
* How to use it 
* What should one do if one wants to contribute it
---
## 4- What does the git clone command do?
* git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location

Syntax:

    git clone [url]
---
## 5- If we want to update the local repository with the remote repository, what command should be executed? 
* We have to use the git pull command 

Syntax:

    git pull
---
## 6- What is the difference between git checkout, git revert and git reset merged?
Checkout:

    Use this to move the HEAD pointer to a specific commit or switch between branches.
    It rollbacks any content changes to those of the specific commit.
    This will not make changes to the commit history.
    Has potential to overwrite files in the working directory.

Revert:

    Rollback changes you have committed.
    Creates a new commit from a specified commit by inverting it. Hence, adds a new commit history to the project, but it does not modify the existing one.
    Has the potential to overwrite files in the working directory.

Reset:

    Use this to return the entire working tree to the last committed state. This will discard commits in a private branch or throw away uncommitted changes!
    Changes which commit a branch HEAD is currently pointing at. It alters the existing commit history.
    Can be used to unstage a file.
---
## 7- What is the difference between git merge and git rebase commands?
* The merge command creates a new commit but the rebase command integrate the changes in the repository remote respectively  
---
## 8- What command is used to see the history of commites? 
* We have to use the git log command 

Syntax:

    git log
---
## 9- What command do we use if we want to see changes to a file? 
* We have to use the git diff command 

Syntax:

    git diff
---
## 10- What is the use of tag? How to create a tag? 
* Tagging is  used to create semantic version number identifier tags that correspond to software release cycles

Syntax:

    git tag [version]
---
## 11- What is the process to participate in a project that managed by git?
* We build our git directory and initial it, then clone the project from the repository and view the logs and status of the git and then make our changes and commit our changes to project and finaly merge them to the  project mainline
---
## 12- What are the branches used for and how can they be integrated? 
* In Git, branches are a part of your everyday development process. Git branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug no matter how big or how small you spawn a new branch to encapsulate your changes. Merging takes your branch changes and implements them into the main branch




