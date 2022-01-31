# hello-world
Hello World repository for Git tutorial

This repository is built step by step in the tutorial.

#
Check status of files in repository
git status

in a compact manner
git status --short

In Shorts these are file annotation
?? - Untracked files
A - Files added to stage
M - Modified files
D - Deleted files

#
add all files in the current directory to the Staging Environment
git add --all or git add -A

#
move from stage to commit for our repo
commit, we should always include a message.
Adding commits keep track of our progress and changes as we work
git commit -m "First release of Hello World!"

Git Commit without Stage
git commit -a -m "Updated index.html with a new line"

#
To view the history of commits for a repository
git log

#
See all the available options for the specific command
git command -help

#
See all possible commands
git help --all

#
Git Branch
a branch is a new/separate version of the main repository
Branches allow you to work on different parts of a project without impacting the main branch.
When the work is complete, a branch can be merged with the main project.
You can even switch between branches and work on different projects without them interfering with each other.

git branch hello-world-image

check branches
git branch

#
Git Checkout
checkout is the command used to check out a branch. Moving us from the current branch,
to the one specified at the end of the command:

git checkout hello-world-image

#
Emergency Branch