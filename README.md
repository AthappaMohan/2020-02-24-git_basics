# 2020-02-24 Git Basics

- `init`: make current folder a git repository
- `status`: see the status of current repository
- `add`: put files into the index (staging area)
- `commit`: commit the files from staging area
  - `commit -m "MESSAGE"`: directly put in single line commit message
- `diff`: look at differences between 2 commit states
- `log`: look at the history
  - `log --oneline`: only get the oneline view
  - `log --online --graph --decorate --all`: see everything in history
- `checkout <hash> <file>`: restore a single file from a point in history
  - `checkout <hash>`: restore the entire folder to that point in time

- index/staging area: files in here will be commited
- `HEAD`: where you are looking at in git history
