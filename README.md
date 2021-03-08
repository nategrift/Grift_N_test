
## Cloning
*Copy folder to computer*
1. `cd Documents`

2. `git clone <github-link>`

## Editing and pushing to cloud

1. `git checkout -b <branch>`

    This switches branches to the branch specified.  The "-b" is creating the branch.
2. `git add .`

    Adds items, or picks them up getting ready to give to git.  *NOTE: Include the "." to add all files that you have edited*
    *NOTE: If you need to undo a `git add .`, then type `git restore --staged .`
3. `git commit -m '<message>'`

    Commits to git. Git now has it, but it is only on our computer. 
4. `git push origin <branch>`

    Commits to GitHub.  Leaves the computer and goes to github so others can see.  the branch is the branch you are on.  And "origin" id talking about where the repository is located, for this it is Github.
    *NOTE: use `git branch` to see what branch you are on*

## Switch to main branch and then get updated branch
1. `git checkout main`

    Switching to the main branch, not creating the breanch but switching because we didn't include the "'-b'
2. `git pull origin main`

    Getting the latest version from github.  It grabs all the files that are different from yours and github.  Making your up to date. 
