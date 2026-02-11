<h2 style="color: teal;" >vid 2<h2>

git status
//shows status

git add "file_name" 
//adds the new file to STAGE

git add -A 
//adds every file inside that specefic folder to the STAGE

git commit -m'comment'
//commits every file inside STAGE and you can add a comment too

<h2 style="color: teal;" >vid 3<h2>

git log
//shows every recent commit that has been commited

<h2 style="color: teal;" >vid 4<h2>

git diff HEAD
//pretty much like git log but it shows details of each commit as well, last commits

git diff --staged
//only shows the files inside stage

git reset file_name
//unstages the file => makes it not staged

git checkout -- file_name
//undos every changes of the specefic file after the last commit

<h2 style="color: teal;" >vid 5<h2>

git branch
//shows every branch that exists, and wich you are currently inside

git branch branch_name
//creates a new branch

git checkout branch_name
//goes to the specefic branch

git merge branch_name
//merges the specefic branch via the branch you are currently inside

//btw ohmyzsh is an npm that shows in wich branch you are currently in

<h2 style="color: teal;" >vid 6<h2>

git rm file_name
//removes the file from git and storage

git branch -d branch_name
//deletes the branch, - pronuons: dash

<h2 style="color: teal;" >vid 7<h2>

git clone URL_address 
//you can copy the clone url of any open src project and edit your own clone from them
//before using clone command you should exits your current branch via cd /..

git push origin master, git push remote_branch_name local_branch_name
//you can push your own code to the origin project
//master is the name of your main branch that you should be currently inside it

git pull origin master
//you can get the origin code from the main project to your own branch

<h2 style="color: teal;" >vid 8<h2>

<h2 style="color: teal;" >vid 9<h2>

<h2 style="color: teal;" >vid 10<h2>

<h2 style="color: teal;" >vid 11<h2>

<h2 style="color: teal;" >vid 12<h2>














