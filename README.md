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