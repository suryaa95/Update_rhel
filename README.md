##################################################################
git config --global user.email “you@example.com”
git config --global user.name “Your Name”
###################################################################################
…or create a new repository on the command line
echo "# bash_script" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/suryaa95/bash_script.git
git push -u origin main
#####################################################################################33
…or push an existing repository from the command line
git remote add origin https://github.com/suryaa95/bash_script.git
git branch -M main
git push -u origin main
##################################################################
git add .
git status
git commit -m "first commit"
git push origin main
git pull origin main
#######################################################################################
Error---
git: rename local branch failed
---------------error: refname refs/heads/master not found
fatal: Branch rename failed
Sol-
If you first checkout master:

#git checkout master
and then create a new branch:

#git checkout -b new_branch
//https://stackoverflow.com/questions/18382986/git-rename-local-branch-failed
#########################################################################
