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

`git whosebranch`

Find out who authored a certain branch

`git diffbase`

Diff the commits on a branch against the most recent common ancestor with another branch

`git git [command]`

Runs `git [command]` if you accidentally type git twice. Works for any number of preceeding git commands.

Bash Completion
===============

A script for doing bash completions is provided in the install directory, $HOME/bin. If
you want to use bash completions, you need to add:

`source $HOME/bin/git-easymode-completions.bash`

to your ~/.bashrc file. You must already have the bash completions for other git commands
functioning.

