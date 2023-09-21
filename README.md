# GitCheat Sheet and Branching Practice
## Overview

Common command reference, and practicing with commits and 
branches.


Stuff Added By Rob1 in Main
More Main Stuff


## Basic Commands
* `git init` - initialize local git repo
* `git add fileName` - stage changed file `fileName`
* `git commit - m "message"` - commit staged 
changes, with commit message "message"

## Info Commands
* `git status` - show status of working directory
* `git log` - list local commit history
* `git log --online` - list local commit history in
compact format
* `git config --list` - show config settings for local repo

## Branching Commands
* `git branch` - list local branches
* `git branch -m newName` - rename current branch to `
newName`
* `git branch branchName` - create local branch `branchName`
* `git checkout branchName` - switch to local branch `
* `git checkout-b branchName` - create and switch to `
branchName`

##Remote Commands
* `git remote add origin url` - configure `url` asa remote
repo, with alias `origin`
* `git push origin branchName` - push local commits to
remote repo `origin` on `branchName`
* `git pull origin branchName` - pull and attempt to merge
remote `branchName` into current local branch

