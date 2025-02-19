# Git Commands Cheat Sheet


  ```bash
  git config --list
  ```

## 2. Initialize Repository

- Initialize a new Git repository:
  ```bash
  git init
  ```

## 3. Clone Repository

- Clone an existing repository:
  ```bash
  git clone <repository_url>
  ```

## 4. Staging and Committing

- Check repository status:
  ```bash
  git status
  ```
- Add a file to staging:
  ```bash
  git add <file>
  ```
- Add all files to staging:
  ```bash
  git add .
  ```
- Commit changes:
  ```bash
  git commit -m "Commit message"
  ```

## 5. Branching

- Create a new branch:
  ```bash
  git branch <branch_name>
  ```
- Switch to a branch:
  ```bash
  git checkout <branch_name>
  ```
- Create and switch to a new branch:
  ```bash
  git checkout -b <branch_name>
  ```
- List all branches:
  ```bash
  git branch
  ```
- Delete a branch:
  ```bash
  git branch -d <branch_name>
  ```

## 6. Merging

- Merge a branch into the current branch:
  ```bash
  git merge <branch_name>
  ```

## 7. Remote Repositories

- Add a remote repository:
  ```bash
  git remote add origin <repository_url>
  ```
- List remote repositories:
  ```bash
  git remote -v
  ```
- Remove a remote repository:
  ```bash
  git remote remove <name>
  ```

## 8. Pushing and Pulling

- Push changes to remote repository:
  ```bash
  git push origin <branch_name>
  ```
- Pull changes from remote repository:
  ```bash
  git pull origin <branch_name>
  ```

## 9. Reverting Changes

- Undo last commit (keep changes):
  ```bash
  git reset --soft HEAD~1
  ```
- Undo last commit (discard changes):
  ```bash
  git reset --hard HEAD~1
  ```

## 10. Viewing History

- View commit history:
  ```bash
  git log
  ```
- View commit history (one line per commit):
  ```bash
  git log --oneline
  ```
- View changes in a commit:
  ```bash
  git show <commit_hash>
  ```

## 11. Stashing

- Save changes without committing:
  ```bash
  git stash
  ```
- Apply stashed changes:
  ```bash
  git stash apply
  ```
- Drop the last stash:
  ```bash
  git stash drop
  ```

## 12. Tagging

- Create a new tag:
  ```bash
  git tag <tag_name>
  ```
- List tags:
  ```bash
  git tag
  ```
- Delete a tag:
  ```bash
  git tag -d <tag_name>
  ```

## 13. Removing Files

- Remove a file from tracking:
  ```bash
  git rm --cached <file>
  ```
- Remove a file from repository and filesystem:
  ```bash
  git rm <file>
  ```

