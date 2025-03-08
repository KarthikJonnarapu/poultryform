# This is a demo of how to use the most widely used or popular Git commands:

# Below commands are used for creating a branch and checkout to that branch and push the branch to origin
git branch  - to check the current branch that user is working
git branch branch-name  - to create the new branch
git branch checkout - to move to the branch that is created newly
git branch push origin - to push the newly created branch to the origin which is the git repository
git worktree list - this command is used when we try to delete the current branch that we are working and it shows in which branch that we are working currently
git checkout -b branch-name - this will create the new branch and checkout's to our newly created current branch

# Below commands are used to delete the branches from local
git branch -d branch-name - is used to delete the local branch - branch will deleted from the local but will be availablein the repo
git branch -D branch-name - it forces the deletion if the branch is not yet been merged also

# Below commands are used to delete the branches from repo 
git push origin --delete branch-name - is used to delete the remote branch - branch will be deleted from repo but avialable in local system

# Below commands are used tp rename the branches in local
git branch -m new-branch-name - this command is used to rename the existing branch in the local
git branch -m old-branch-name new-branch-name - this is used to rename when we are not in the same branch in short rename any branch that we want

# Below commands are used to rename the remote branches
git push origin -m new-branch-name
git push --set-upstream origin branch-name - setting the upstream is so important that to ensure that your local changes are being properly linked to the corresponding remote branch
                                           - and this also makes the operations like git push and git pull work without needing to sepecify the remote branch each time.