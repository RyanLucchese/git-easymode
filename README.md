git-easymode
===============

A collection of scripts to make life easier for git users using gitflow

Installation
===============

./install.sh

If you don't want to install to $HOME/bin, cp git-\* to another location in $PATH

Usage
===============
`git new-branch`

Create a new branch tracking origin/develop and push it up to the origin

`git update-branch`

Merge your current branch with the latest origin/develop and prune branches on the origin

`git pull-all`

Find every git repository below the current directory and execute git pull on it

`git checkout-modified-files`

Checkout all modified files that are not staged in the current directory

`git ls-assume-unchanged`

List all files marked as --assume-unchanged

`git whose-branch`

Find out who authored a certain branch

`git branch-diff`

Diff the commits on a branch against the most recent common ancestor with another branch
