---
layout: post
title: "Getting Started with Git"
date: 2018-8-15
categories: Developer Guides
---

**Table of Contents**

1. [About this guide](#about)
2. [What is Git](#git)
3. [Common Git Commands](#common-git-commands)

<br/>

## About this guide <a name="about"></a>
This document aims to help beginners learn the basic functionality of the Git version control system.

<br/>

## What is Git? <a name ="git"><a/>

Git is a [free and open source](https://git-scm.com/about/free-and-open-source) software that is best known as a version control system. A version control system, or VCS, is a tool that tracks the history of changes of a file or set of files. This is particulary useful when teams collaborate on a project together. As the project evolves, teams can run tests, fix bugs, and contribute new code with the confidence of knowing that any previous version can be recovered at any time.[1]

In brief, Git is a tool that lets developers see the entire timeline of their changes, decisions, and progression of any project in one place.

<br/>

## Git commands <a name="common-git-commands"></a>

Git commands can be executed directly from a command-line interface (CLI) or through a third-party desktop application such as [GitHub Desktop](https://desktop.github.com/).

**Note**: Before getting started, make sure to have Git installed on your local computer. To install Git for your computer's operating system, follow the installation instructions at [Getting Started - Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).


Some of the most common Git commands include the following: 

  `git init` initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.

  `git clone` creates a local copy of a project, which already exists remotely. The clone includes all of the project files, history, and branches.

  `git commit` saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything thatâ€™s been staged with git add will become a part of the snapshot with git commit.

  `git status` shows the status of changes as untracked, modified, or staged.
  git branch shows the branches being worked on locally.

  `git merge` merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the master branch for deployment.

  `git pull` updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.

  `git push` updates the remote repository with any commits made locally to a branch.

<br/>

**References**

[1] Source: ["Getting Started - About Version Control"](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)_
