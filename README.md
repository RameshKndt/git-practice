# git-practice
git commands show case
GIT REBASE - EDIT
Approach-1
git rebase -i @~1   # Show the last 1 commits in a text editor

Find the commit you want, change pick to e (edit), and save and close the file. Git will rewind to that commit, allowing you to either:

use git commit --amend to make changes, or

git rebase --continue
git push --force
