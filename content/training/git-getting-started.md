---
title: "Git: Getting Started"
topic: true
subjects: ['Version Control']
draft: false
intro: |
  A Version Control system is a fundamental tool for developers, analysts and reseachers. It provides the following benefits:

    - a complete history of revisions (and the ability to revert to older versions);
    - backups; and
    - enables collaboration.

  Git is the most pervasive Version Control system today. It works well on all projects, from a few files and a single developer to thousands of files and hundreds of developers.
duration: 1 day
outcomes: |
  After this course you'll be familiar with how Git works and primed to start using it on your own projects.
---

- Why Version Control?
	- Version control systems
	- Git: A short history
- Setting Up Git
	- `git config` --- creating an identity
- Creating a Repository
	- `git init`
	- Quick tour of `.git` folder
- Committing to the Repository
	- `git add` --- adding files to the staging area
	- `git commit` --- moving files from the staging area to the repository
	- `git status`
	- Ignoring files with `.gitignore`
- Tracking Changes
	- `git log` --- browse commit messages
	- `git diff`
- Retrieving from the Repository
	- `git checkout`
	- Referencing commit using a hash
- Branches
	- Creating a branch
	- Switching between branches
	- `git log --graph` --- visualising branches
	- Merging a branch
	- Merge conflicts
	- Deleting a branch
- Git as a Tool for Collaboration
- Remote Repository
	- What's the deal with remotes?
	- `git clone` --- cloning a Remote Repository
	- Clone versus fork?
	- `git remote` --- adding and removing a remote
	- `git pull`
	- `git fetch`
	- `git push`
- UIs
	- Command Line versus UI
	- [GitKraken](https://www.gitkraken.com/)
