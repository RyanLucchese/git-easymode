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

`git checkout-modified-files`

Checkout all modified files that are not staged in the current directory

`git ls-assume-unchanged`

List all files marked as --assume-unchanged
