#Git Class WorkFlows

#Getting Latest Changes

1. Commit all local changes [git add -A;git commit -m "message"]
2. Switch to master branch [git checkout master]
3. Pull changes from jp [git pull jp master]
4. Create a new branch [git checkout -b new_branch_name]

#New Exercise

1. Create a new branch for the exercise [git checkout -b new_branch_name]
2. Work on code

#Pushing Changes For JP To Look At

1. Commit all local changes (on your non master branch)
2. Switch to master branch [git checkout master]
3. Merge changes from the branch you were working on [git merge branch_name]
4. Push master back to github
5. Switch back to the branch you were working on/create a new branch


