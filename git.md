## Branch

- `git branch <newbranch>` - Creata new branch
- `git branch -d -r <branchname>` - Delete the remote-tracking. (The next fetch or pull will create them) 
- `git branch -d <branchname> -Delete branch
- `git branch -a` - List both remote-tracking branches and local branches.

## Checkout

- `git checkout -b <newbranch>` - Specifying -b causes a new branch to be created 
- `git checkout <newbranch>` - To prepare for working on <branch>, switch to it by updating the index and the files in the working tree, and by pointing HEAD at the branch

## Stash

- `git stash` - Stash the changes in a dirty working directory away
- `git stash pop` - Remove a single stashed state from the stash list and apply it on top of the current working tree state, i.e., do the inverse operation of `git stash save`. The working directory must match the index.
- `git stash apply` - Like pop, but do not remove the state from the stash list. Unlike pop, <stash> may be any commit that looks like a commit created by stash save or stash create.
- `git stash show` - Show the changes recorded in the stash entry as a diff between the stashed contents and the commit back when the stash entry was first created. When no <stash> is given, it shows the latest one. 
- `git stash list` - List the stash entries that you currently have
- `git stash clear` - Remove all the stash entries. Note that those entries will then be subject to pruning, and may be impossible to recover
