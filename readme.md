![Uploading HTML5_logo_and_wordmark.svg.png…]()
q:Tell me how to remove them locally and remotely.

a:
To delete a remote branch
git push origin :branch_name

To delete a local branch
git branch -d branch_name


q:Tell me how to checkout another branch without commit
changes

a: we going to use stach
stach works : 
Saves my working directory changes 
Restores my working directory to the last committed state.
Stores the stashed changes in a stack so you can retrieve or reapply them later.

1- save on stash   --> git stash
2-view all stashes --> git stash list
3- apply on stash  --> git stash aply --> Re-applies the most recent stash.
4- clear  --> git stash clear  --> Deletes all stashes.


q:Tell me how to list tags.

a: git tag --> on master


q:tell me how to delete tag locally and remotely.

To delete remote tag
git push origin --delete v1.0

To delete local tags
git tag -d v1.0
