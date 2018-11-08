---
layout: post
title: "Getting Started with Git"
date: 2018-9-15
categories: Guides
---

## What is Git? 
---

Git is a free and open source distributed version control system designed to handle everything from small to huge projects with speed and efficiency[1].

Using Git is similar to working with a regular software project. You’re still writing code in files and storing those files in folders. The main difference, however, is that you have access to a plethora of Git commands to manipulate those files.

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
