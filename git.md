# Git Basics
## Git clone with ssh
```
git clone git@github.com:omatarasu/learning.git
```
> omatarasu - username, learning.git - repo name

## Git Branch 
```
git branch                   # show branch
git branch dev               # create branch dev
git checkout dev             # change branch to dev
```
## Git Merge
```
git checkout dev             # switch to dev
git pull                     # download some changes
git add . test.md            # add new file
git commit -m "add test.md"  # commit changes
git push                     # push changes
git checkout main            # switch to main
git pull                     # download somw changes
git merge dev                # merge dev to main
git push                     # push changes
```