---
layout: post
title: "Getting Started with Git"
date: 2018-9-15
categories: Guides
---

### About this guide
---

This document aims to help beginners learn the basic functionality of the Git version control system.

<br/>

### What is Git? 
---

Git is a [free and open source](https://git-scm.com/about/free-and-open-source) software that is best known as a version control system. A version control system, or VCS, is a tool that tracks the history of changes of a file or set of files. This is particulary useful when teams collaborate on a project together. As the project evolves, teams can run tests, fix bugs, and contribute new code with the confidence of knowing that any previous version can be recovered at any time.[1]

In brief, Git is a tool that lets developers see the entire timeline of their changes, decisions, and progression of any project in one place.

<br/>

### Basic Git commands
---

These commands can be executed directly from the command line or through an application like [GitHub Desktop](https://desktop.github.com/). 


**Here is a list of common Git commands:**


`git init` initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.

<br/>

`git clone` creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.


<br/>

`git commit` saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.

<br/>

`git status` shows the status of changes as untracked, modified, or staged.
git branch shows the branches being worked on locally.

<br/>

`git merge` merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the master branch for deployment.

<br/>

`git pull` updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.

<br/>

`git push` updates the remote repository with any commits made locally to a branch.

<br/>

#### References
---

[1] Source: _["Getting Started - About Version Control"](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)_
