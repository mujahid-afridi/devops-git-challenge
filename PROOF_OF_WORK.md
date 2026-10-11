# PROOF OF WORK

## 1. Git Commit History

The following output shows the commit history of the project.

3b354e1 (HEAD -> main, origin/main) Merge pull request #1 from mujahid-afridi/development
76d9b5a (origin/development, development) fix: resolved merge conflict
3886106 (origin/staging, staging) fix: staging label
f973a5c feat: updated script with staging env
2ddae75 feat: initial commit with deploy script

## 2. Reflection Questions

### Q1: What is the difference between Git (local tracking) and GitHub (cloud platform)?

Git is a distributed version control system that tracks changes in files and manages project history. It allows developers to create commits, work with branches, and manage changes on their local computers. GitHub is a cloud-based platform that hosts Git repositories online. It enables developers to share code, collaborate with others, create pull requests, and review changes through a web interface.

### Q2: Explain the three architecture stages: Working Directory, Staging Area, and Local Repository.

The Working Directory is the project folder where we create, edit, and delete files. The Staging Area contains the changes we have selected for inclusion in the next commit using commands such as `git add`. The Local Repository stores committed snapshots and the project's version history. The usual workflow is to modify files in the Working Directory, stage selected changes, and commit them to the Local Repository.

### Q3: What is the difference between `git stash pop` and `git stash apply`?

Both `git stash pop` and `git stash apply` restore previously stashed changes to the working directory. The `git stash pop` command applies the changes and normally removes the corresponding stash entry after a successful application. The `git stash apply` command applies the changes but keeps the stash entry in the stash list. Therefore, `git stash apply` is useful when we want to reuse the same stashed changes or keep a backup before removing them.

### Q4: What is the difference between `git fetch` and `git pull`?

The `git fetch` command downloads new commits and other updated information from a remote repository without integrating those changes into the current branch. It allows developers to inspect remote updates before deciding how to integrate them. The `git pull` command fetches remote updates and then integrates them into the current branch, usually through a fast-forward or merge. Therefore, `git fetch` is useful for checking updates first, while `git pull` is useful when we want to retrieve and integrate remote changes.
