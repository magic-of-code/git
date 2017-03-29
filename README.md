# Git

This is a class that covers the following topics on how to use git.

1. [What and Why](#what-and-why)
1. [Setup](#setup)
1. [Repository Creation](#repository-creation)
1. [Adding Files and Making Changes](#adding-files-and-making-changes)
1. [Branching and Merging](#branching-and-merging)
1. [Collaborating](#collaborating)
1. [Bonus Material](#bonus-material)
1. [Additional Resources](#additional-resources)

## What and Why

## Setup

## Repository Creation

## Adding Files and Making Changes

## Collaborating

## Bonus Material

### Compact Log Command

```shell
git log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
```

### Private Repositories

By default, GitHub makes your repositories public. This is great for [open source](https://en.wikipedia.org/wiki/Open-source_software) work.

If you want your work to be private, you either need to

* Have a student account
* Pay for GitHub
* Switch to another service like BitBucket, which gives you a few free private repositories

### Deleting Branches

To delete a branch, you want to run

```shell
git branch -D name-of-branch
```

Replace `name-of-branch` with whatever the name of your branch is.

## Additional Resources

In no particular order, here are a few additional resources on git

* https://try.github.io
  * This is a tutorial sponsored by GitHub and goes through everything covered in this class with a few more basic commands.
* http://gitimmersion.com/
  * This is an in depth step by step guide that goes through everything in this class and it goes even more in depth.
* http://rogerdudler.github.io/git-guide/
  * This is a good, quick reference to use when you forget a command.
