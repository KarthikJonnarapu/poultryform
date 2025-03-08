# This is a demo of how to use the most widely used or popular Git commands:

# Below commands are used for creating a branch and checkout to that branch and push the branch to origin
git branch  - to check the current branch that user is working
git branch branch-name  - to create the new branch
git branch checkout - to move to the branch that is created newly
git branch push origin - to push the newly created branch to the origin which is the git repository
git worktree list - this command is used when we try to delete the current branch that we are working and it shows in which branch that we are working currently
git checkout -b branch-name - this will create the new branch and checkout's to our newly created current branch

# Delete commands - local branches
git branch -d branch-name - is used to delete the local branch - branch will deleted from the local but will be availablein the repo
git branch -D branch-name - it forces the deletion if the branch is not yet been merged also

# Delete commands - remote branches
git push origin --delete branch-name - is used to delete the remote branch - branch will be deleted from repo but avialable in local system

# Rename commands - local branches
git branch -m new-branch-name - this command is used to rename the existing branch in the local
git branch -m old-branch-name new-branch-name - this is used to rename when we are not in the same branch in short rename any branch that we want

# Rename commands - remote branches
git push origin -m new-branch-name
git push --set-upstream origin branch-name - setting the upstream is so important that to ensure that your local changes are being properly linked to the corresponding remote branch
                                           - and this also makes the operations like git push and git pull work without needing to sepecify the remote branch each time.

                                        
# Add files and commit
git add file-name - this will add only the required files to commit
git add . - this will all the newly created or modified files to your commit history

# Shows commit history
git log - this shows the detailed view of the commit history
git lon --oneline - this shows the full commit history at one short very clearly

# Shows difference between 2 commits
git diff - this shows the differ
git diff commit-id1 commit-id2 - this will show the code difference from both the commit ids