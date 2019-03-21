# emf
Empirical Methods in Finance

In this repository we will be able to work on projects and assignments.

Here I would like to share some Git commands:
git config --global user.name 'Kai Banto'
# add file to our repository with:
git add filename.ext
git status
# track/untracked files
git add *.ipynb  # adds every file with this extension
git add .  # adds all files to track
git commit
# --> vim opens: click i, escape, :wq
git commit -m 'changed assignment 1'  # to avoid vim
touch .gitignore
touch log.txt
## Create a branch:
git branch <mybranch>
git commit -m 'new branch'
## Switch branch
git checkout <mybranch>
## Come back to master:
git checkout master
## Merge
git merge <mybranch>  # --> i, comments, escape, :wq
git add README.md
## check if there are any remotes:
git remote
git remote add origin https://github.com/kbantoec/myappsample.git
git push -u origin master
## Change remote
git remote set-url origin https://github.com/KaiBanto/emf.git
git push --help
git pull -h

