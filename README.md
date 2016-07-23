# github-notes

Create the repository in https://github.com
Add .gitignore and Licence, create default readme.

git config --global credential.helper "cache --timeout=3600"
git config --global credential.helper cache
git config --global user.name "Fredrik Safstrom"
git config --global user.email ...

On the computer:
git clone https://github.com/alamorobotics/github-notes
cd github-notes
git remote -v
origin  https://github.com/alamorobotics/github-notes (fetch)
origin  https://github.com/alamorobotics/github-notes (push)
git branch update-Readme
git checkout update-Readme
git branch
  master
* update-Readme

[Do some work...]

git add .
git status
On branch update-Readme
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   README.md

git push --set-upstream origin update-Readme
git push
git checkout master
git merge update-Readme
git push

git pull
git add .
git status
git commit
git push

