# Git Cheatsheet

## Create and Checkout a New Branch

create a new branch off the current branch

```sh
git checkout -b branch_name_here
```

## Stage File(s) For Commit

single file

```sh
git add sessions/exercise1/yay/session.XX.md
```

all changed/updated files in the directory tree 

```sh
git add .
```

## Commit Changes to local branch

```sh
git commit -m "your message here"
```

## Publish a local branch

take your local branch and push it to a remote repository

```sh
git push -u origin BRANCH_NAME_HERE
``` 

## Other Resources

[gitlab git cheat sheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)

[github git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
