#demo for git tutor
!demo for git tutor
#check from local machine 
git --version
git help config
git config --help

#make dir  gittest
mkdir gittest
#move to gittest
cd gittest
#initalize
git init
#local path (Initialized empty Git repository in C:/Users/colin/gittest/.git/)
#batch
git status
#add something in gitdemo.text

git add gitdemo.txt

git commit -m "committing a text file"

#clear
clear 

#link git account
git config --global user.username colinwolf911

#copy the link of remote reposity from git
https://github.com/colinwolf911/walkthough-git.git
#link to remote 
git remote add origin https://github.com/colinwolf911/walkthough-git.git

#push to local to remote
git push origin master
#under master branch 

