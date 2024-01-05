# github-tutorial
this is a tutorial to see how git and github works.
<br>
Author - Harshajit Das
<br>
1. You have to configure git using git config.
   Here we provide name and email.
   git config --global user.name "harshajit88"
   git config --global user.email "harshajit88@hotmail.com"
2. Create a local folder, open with VS code
   clone your repo using git clone
3. You can check the status of the repo using git status
   there are 4 status : untracked, modified, staged and unmodified
4. Next task is to add and commit.
   git add . adds all files in the git staging area
   git commit -m "message" commits/records all the changes in git local
5. Final step is to push the changes from local to remote
   git push origin main
