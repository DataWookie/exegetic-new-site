---
title: "Git"
topic: true
subjects: ['Version Control']
draft: false
who: |
  The course is for students, academics and professionals. Version Control is not just for developers. It's an indispensable tool for anybody who creates content on a computer (for example, source code, documents, presentations or web sites). It also facilitates collaboration between mutliple people working on the same set of files.
intro: |
  A Version Control system is a fundamental tool for developers, analysts and reseachers. It provides the following benefits:

    - a complete history of revisions (and the ability to revert to older versions);
    - backups; and
    - enables collaboration.

  Git is the most pervasive Version Control system today. It works well on all projects, from a few files and a single developer to thousands of files and hundreds of developers.
duration: 1 day
outcomes: |
  After this course you'll be familiar with how Git works and primed to start using it on your own projects.
setup: |
  1. Install [Git](https://git-scm.com/downloads).
  2. Install the [Putty](https://www.putty.org/) SSH client (only Windows users).
  3. Create an account on [GitHub](https://github.com/).
  4. Watch this: https://www.youtube.com/embed/SWYqp7iY_Tc
  5. Read the paper "<a href="/pdf/10.1080-00031305.2017.1399928.pdf">Excuse me, do you have a moment to talk about version control?</a>" by Jennifer Bryan.
        - Why is version control important, and how does Git manage version control?
        - Why is Git particularly useful for developers working with R?
        - What is one of the biggest problems with using Git and GitHub for collaboration?
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
	- Writing a good commit message
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
	- Using GitHub, GitLab or BitBucket
	- `git clone` --- cloning a Remote Repository
	- Clone versus fork?
	- `git remote` --- adding and removing a remote
	- `git pull`
	- `git fetch`
	- `git push`
- UIs
	- Command Line versus UI
	- [GitKraken](https://www.gitkraken.com/)
