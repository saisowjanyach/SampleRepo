commandsusedforgit.txt	  index.html  test.txt
Git\ Commands\ used.docx  readme.txt


Learning git 
using raghav pal tutorial

Here are some steps:


Step 1 : check if git is already installed git --version 
Step 2 : download and install git 
Step 3 : add your project to git 
Step 4 : commands to config email, username of github

git config --global user.email "yourGitHub@email.com" 
git config --global user.name "yourGitHubusername" 

>  to initialize git : git init 
>  to get git status:  git status 
>  to add the files to git we use: git add 
>  to commit the files to git we use where … is message about this commit:
git commit -m “…..” 
>  to add the git to remote repository in github we use : 
git remote add origin https://github.com/saisowjanyach/SampleRepo.git
>  to push the git to github we use: 
git push -u origin master 
> to get git log we use this: git log 
> to get git help we use: git —help 
Step 5 : adding project to remote repository (github)

 
Today we will learn ——————————— 
1. What are branches 
2. How to create branch 
3. How to checkout branch 
4. How to merge branch to master 
5. How to delete branch (local and remote)
 _________________________________________ 
Step 1 : Create branch git branch “branch name”
Git branch Newbranch
 Step 2 : Checkout branch git checkout “branch name” 
Git Checkout “Newbranchname”
Step 3 : Merge new branch in master branch git merge “branch name”
Git push -u origin “newbranchname” eg: git push origin samplerepobranch
 Step 4 : Delete branch 
Git branch -d branchname  - this will delete branch from local
Git push origin –delete branchname – this will delete branch from remote




 
Step 1 : Github - Repository - Settings - integration & services - add email Step 2 : Test and validate by making some change in the project

Step 2 : Test and validate by making some change in the project
