<h2 style="color: green;" >مقدمه‌ای بر کنترل نسخه (Version Control)<h2>

diff file_one file_two
//shows which lines have been changed

diff -y file_one file_two
//shows two files beside each other

diff -u file_one file_two
//shows more detail

patch main_file < patch_file

<h2 style="color: green;" >به‌کارگیری گیت<h2>

git init
//after installing git on your pc do this command in the folder you wanna use git
//it creats a hidden directory named .git

git add file_name
//moves that specefic file from unstaged/untracked to staged

git commit -m'comment'
//moves every file inside the stage to cloud
