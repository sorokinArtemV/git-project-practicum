# Git Commands Cheat Sheet

## 📌 Basic Commands

- **Initialize a repository**
  ```sh
  git init
  ```
  Initializes a new Git repository in the current directory.

- **Clone a repository**
  ```sh
  git clone <repository_url>
  ```
  Creates a local copy of a remote repository.

## 🔄 Working with Changes

- **Check repository status**
  ```sh
  git status
  ```
  Shows modified files and untracked changes.

- **Stage changes**
  ```sh
  git add <file>
  ```
  Adds a file to the staging area.
  ```sh
  git add .
  ```
  Stages all changes in the repository.

- **Commit changes**
  ```sh
  git commit -m "Your commit message"
  ```
  Saves changes to the local repository with a message.

## 📜 Branching & Merging

- **List all branches**
  ```sh
  git branch
  ```
  Displays all local branches.

- **Create a new branch**
  ```sh
  git branch <branch_name>
  ```

- **Switch to a branch**
  ```sh
  git checkout <branch_name>
  ```
  or
  ```sh
  git switch <branch_name>
  ```

- **Merge a branch**
  ```sh
  git merge <branch_name>
  ```
  Merges the specified branch into the current branch.

## 🌍 Working with Remotes

- **Add a remote repository**
  ```sh
  git remote add origin <repository_url>
  ```

- **Push changes to a remote repository**
  ```sh
  git push origin <branch_name>
  ```

- **Pull changes from a remote repository**
  ```sh
  git pull origin <branch_name>
  ```

## 🕵️‍♂️ Viewing History

- **Show commit history**
  ```sh
  git log
  ```
  Displays commit history.
  ```sh
  git log --oneline --graph --all --decorate
  ```
  Compact and visual commit history.

- **Show file changes**
  ```sh
  git diff
  ```
  Shows unstaged changes.
  ```sh
  git diff --staged
  ```
  Shows staged changes.

## 🛠 Undoing Changes

- **Unstage a file**
  ```sh
  git reset <file>
  ```
  Removes a file from the staging area.

- **Undo last commit**
  ```sh
  git reset --soft HEAD~1
  ```
  Moves HEAD back by one commit, keeping changes staged.
  ```sh
  git reset --hard HEAD~1
  ```
  Completely removes the last commit.

## 📎 Helpful Links

- [Official Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://docs.github.com/en/get-started)
