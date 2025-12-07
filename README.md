# Git Commands Practice

Short notes and examples of the Git commands I learn and practice.

---

## 🔹 Basic Commands

- `git init`  
  Initialize a new git repository.

- `git status`  
  Show the current state of the working directory and staging area.

- `git add <file>`  
  Add changes to the staging area.

- `git commit -m "message"`  
  Save your changes with a clear message.

- `git log`  
  View commit history.

---

## 🔹 Branching

- `git branch`  
  List branches.

- `git branch <name>`  
  Create a new branch.

- `git checkout <branch>`  
  Switch to a branch.

- `git merge <branch>`  
  Merge a branch into the current one.

---

## 🔹 Remote

- `git remote -v`  
  Show connected remotes.

- `git push`  
  Upload commits to GitHub.

- `git pull`  
  Fetch and merge changes from GitHub.

---

#

---

Advanced Git Commands Practice
-

Short notes and examples of the advanced Git commands I learn and practice.

---

## 🔹 Clone & Fetch

- `git clone <url>`

Download a repository from GitHub to your local machine.


- `git fetch`

Get updates from the remote without merging them.

---

## 🔹 Stashing

- `git stash`

Temporarily save uncommitted changes.


- `git stash pop`

Restore stashed changes and remove them from stash history.

- `git stash list`

Show all stored stashes.

---

## 🔹 Reset & Revert

- `git reset HEAD <file>`

Unstage a file without removing changes.

- `git reset --soft HEAD~1`

Undo the last commit but keep the changes in the working directory.

- `git revert <commit-hash>`

Create a new commit that undoes the changes from a specific commit.

---

## 🔹 Diff & Show

- `git diff`

Show changes not staged for commit.

- `git diff --staged`

Show changes staged for the next commit.

- `git show <commit-hash>`

Display details about a specific commit.

---

## 🔹 Branch & Rename

- `git branch -m <old> <new>`

Rename a local branch.

- `git push origin -u <new>`

Push the renamed branch to GitHub.

- `git push origin --delete <old>`

Delete the old branch from GitHub.

---

## 🔹 Remove & Clean

- `git rm <file>`

Remove a file from the repository and stage the deletion.

- `git clean -f`

Remove untracked files from the working directory.

---

## 🔹 Tags

- `git tag <tag-name>`

Create a tag (often used for releases).

- `git push origin <tag-name>`

Upload a tag to GitHub.

---

## 🔹 Rebase

- `git pull --rebase origin main`

Pull updates from GitHub and reapply your commits on top.

---

## 🔹 Blame

- `git blame <file>`
  
Show who last modified each line of a file.
