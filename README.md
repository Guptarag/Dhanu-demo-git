# github-demo
This is my github learning tutorial
hii
<h1> to configure git </h1>
1. git config --global user.name "username" <br>
2. git config --global user.email "userEmail"
<br>
3. git config --list


<h1> to clone the repository or get status of the file</h1>
1. git clone "repository link" <br>
2. git status

<h1> add / commit files</h1>
1. git add "filename"       --> to add single file (without adding files we cannot commit) <br>
2. git add .                --> to add all files at a time
<br>
3. git commit -m "add a comment"

<h1> init commands </h1>

1.git init
<br>
2. git add remote <..link>
<br>
3. git remote -v (verify remote)
<br>
4. git branch (to get branch name)
<br>
5. git branch -M main (to rename branch )
<br>
6. git push orgin main 
<br>
7. git push -u (to push all upstream files)
<h1> branch commands </h1>
1. git branch (to get branch name)
<br>
2. git branch -M main (to rename branch )
<br>
3. git checkout -b <..branchName> (to create a branch)
<br>
4.  git checkout branchName  (to navigate branches)
<br>
5.  git checkout -d <..branchName> (to delete branch. here we cannot delete current branch if we have to delete the branch we have to navigate to another branch and delete that particular branch)