# git init -b main
git init -b main

git remote add origin

git remote -v

git fetch origin main

git pull origin main --rebase

git remote -v

git push -u origin main

# git checkout -b <new-branch-name>

1. git checkout -b <new-branch-name>

2. git checkout new-branch-name

3. git push -u origin new-branch-name

4. git branch --delete new-branch-name <git delete local branch> 

5. git push origin -d remote-branch-name <git delete remote branch>

# git remove remote commit

1. git log the log command is used to track a branch's commit history
2. git reset --soft <commit ID>
3. git reset <filename>
   
# git remove local commit

1. git reset --soft HEAD^ or git reset <filename>
2. git checkout <filename>


