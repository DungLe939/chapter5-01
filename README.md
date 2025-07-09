# 1. Git and GitHub overview
## 1.1 What is Git?
- Git is free.
- Open Source.
- Control System.
- Handle Project.
## 1.2 Why Git ?
- Can oversee the change of the files.
- Can roll back (time travel) every time.
## 1.3 Git History
- Git is created by Linus Torvalds, father of the Linux.
- Around 2005, it is hard to control version of software you need pay. much for the control version and Linus had created that.
- The fact of the name Git is mean "unpleasant person" in English slang.
## 1.4 Git Workflow/ Architecture
![[Pasted image 20250708082041.png]]
## 1.5 The different between Git and GitHub
- It is very different.
- GitHub like a bucket to store your code, image this is Google Photo which you can adjust image.
- Git is tool to take a photo.
# 2.1 Terminal vs GUI (Git client)
Which ways you can learn git?
## 1. Git client (GUI)
- Git Kraken.
- Source Tree.
- GitHub Desktop.
## 2. Terminal
- Terminal is better.
- It is flexible.
# 3. Repository
## 3.1 Concept
- Repository: like folder in GitHub.
## 3.2 Create repository in GitHub
- To create repository.
```
Step 1: Click avatar in GitHub.
Step 2: Click "Your repositories".
Step 3: Click green button "New".
Step 4: Enter name of repository.
Step 5: Scroll down and create.
```
- After step 5: you can choose 2 case
- Case 1: New repo.
- Case 2: Push an existing repo.
## 3.3 Local Git repository
- git config --list
- git config --list --show-scope
- git config --global user.name "your Name"
- git config --global user.email "your_email@example.com"
- `Your email is email you login in Github`.
-  Three level: local, global, system
## 3.4 Initialize Git
- `code .` : open vs code
- `git init` : don't init so much time
- U is untracked, vscode don't know about the change
- `ls` and `ls -a`: in git bash
- `dir`: list file
- `mkdir hello`: create folder
- `echo "" > text`: tao txt
- `del yourFile`: xoa file
```
ctrl + `: de bat terminal trong vs code
```
- `git status`
- untracked is chua tung dc khai bao voi git
- `git add .`: dau cham the hien trong thu muc
- `git commit -m "text"`
- `git commit` : linux is on and you can press `i` mean insert then type message, press esc then :wq mean write and quit
## 3.5 Remote Repository
- `git remote`: check name
- `git remote add "yourNameRepo" "yourRepoLink"`: connect with github
- `git remote show "yourNameRepo"` : check link of name repo
- In case you set repo link wrong you can set it
- `git push [yourRepoName] [yourBranch]`: push your code in github
- `git push -u origin master`: set branch you use so that you dont need to git push origin master
## 3.6 Working Directory/ Staging Area/ Repository
- Changes: is write, them, sua, xoa
- Staged Changes: nguyen lieu duoc chon loc chuan bi duoc commit
- And commit
