# git init -b main
git init -b main

git remote add origin

git remote -v

git fetch origin main

git pull origin main --rebase

git remote -v

git push -u origin main

# git checkout -b <new-branch-name>

git checkout <new-branch-name>

git push -u origin <new-branch-name>


# git remove remote commit

1. git log the log command is used to track a branch's commit history
2. git reset --soft <commit ID>
3. git reset <filename>
   
# git remove local commit

1. git reset --soft HEAD^ or git reset <filename>
2. git checkout <filename>


