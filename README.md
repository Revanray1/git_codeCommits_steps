# git_codeCommits_steps

1. First Creating Repo in Github  then Working on local

 -   git clone https://github.com/SAMPLE_LINK.git
 -   cd react-Hooks-sample
 -   Create a new file or make a changes in existing file (README file)  (Or create any file you need)
 -   add userName and email  - > git config user.name "userName"  ,  git config user.email "userEmail"
 -   git add .
 -   git commit -m "Initial commit"
 -   git push origin main.


2. Already code existing in local , then created a new repo and commiting the code into git.

- go to project folder  -  cd /path/to/your/existing/project
- git init
- git remote add origin https://github.com/SAMPLE_LINK.git
- git add .
- git commit -m "Initial commit"
- git push -u origin main

- if error: src refspec main does not match any this error occurs.
 -- > git branch 
 -- > If your branch is master, you can rename it to main (to match your GitHub repository) with [if necessary]
 -- > After ensuring you're on the main branch and have at least one commit, try pushing again: use -> git push -u origin main
 -- > If your branch was originally master and you don’t want to rename it, you can push using master like this: use -> git push -u origin master
   




