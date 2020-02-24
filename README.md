# Git Basics

## Local

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

## Remotes

- remote: anywhere you didn't `init` or `clone`
  - `remote add origin <URL>`: adds the url as a remote named `origin`
  - `remote -v`: see your remotes
- `push`: send code to our remote
  - `push origin master`
- `pull`: get code from our remote (does a `fetch` and `merge`)
  - `pull origin master`
