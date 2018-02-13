#RENOMEAR BRANCH

# rename the local branch to the new name
git branch -m old_name new_name 

# delete the old branch on remote - where <remote> is eg. origin
git push <remote> --delete old_name

# push the new branch to remote         
git push <remote> new_name
