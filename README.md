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

### Why are they useful?

[git](https://git-scm.com/) and [GitHub](https://github.com/) prevent you from losing work if you accidentally delete your files, or something terrible happens to your computer.

They also make it easy to collaborate with others on the same project without worrying about if everyone is on the same version.

You are also provided a history of every change, and if working with others, who made those changes.

### What is git?

git is a [command line (or terminal, or command prompt)](https://en.wikipedia.org/wiki/Command-line_interface) tool that lets you easily track changes to your files so you no longer have to name files doc_version_1.txt, doc_version_2.txt, doc_final.txt, doc_final_final.txt.

git also makes it easy for you to separate your work into chunks (more commonly known as [branches](#branching-and-merging) and merge everything back together later.

You may hear it called a version control system, or VCS

### What is GitHub?

GitHub is a website that works with git, so you can store your files online, similar to Dropbox or Google Drive.

With GitHub being online, that makes it easy for you to share your work with others, and collaborate on a project together.

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
