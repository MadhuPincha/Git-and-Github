# This is Git & Github Tutorial.
### git add(track the files)->git commit(goes to staging env)->git push(only files in staging env will be pushed to main branch)
### step-0 Create a file--README.md (add some comments)
### Step-1 git --version
### Step-2 git init
### step-3 git config --global user.name "Madhu Pincha" (For first time)
### step-4 git config --global user.email "mpincha1999@gmail.com" (For first time)
### step-5 git status (untracked files)
### step-6 git add README.md
### step-7 git status (tracked README)
### step-8 make another file--requirements.txt (add some libraries)
### step-9 git status (modified:README, untracked file:requirements, multiple changes are there, so...)
### step-10 git add . (for tracking all changes, . means all)
### step-11 git status (changes committed, now we have 2 files)
### cls--clear screen
### step-12 git commit -m "my first commit" (files changed, insertions)
### step-13 git status (nothing is there now)
### How to revert commit?, Can we commit without staging?
### step-14 git branch (master now, we have to change it to main branch)
### step-15 git branch -M main
### step-16 git branch (now main)
### step-17 git remote add origin https://github.com/MadhuPincha/Git-and-Github.git
### step-18 git remote -v
### step-19 git push -u origin main (push from origin to main)
### step-20 Make some changes & git add . & to restore (git restore --staged)

### step-21 git branch dev1 (How to create new branch?)
### step-22 git branch (all branches)
### step-23 git checkout dev1 (switch to dev1 branch), make changes & check status now
### step-24 checkout to main then dev1 and you will see the changes.
### step-25 merge branches (git merge dev1)-check current branch (git branch)
### step-26 again check branch, git branch (we are in main)
### step-37 continue...(changes, add, commit, push)
### step-38 make new branch, jump to that branch, make changes (dev2)
