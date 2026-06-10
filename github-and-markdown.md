# GitHub and Markdown

## Markdown basics

- `#` = H1, `##` = H2, `###` = H3
- `**bold**` = **bold**
- `*italic*` = _italic_
- `---` = horizontal line
- `> "quote"` = blockquote

## Images and links

- `![alt text](url)` = image
- `[link text](url)` = link
- `<img src="url" width="800" />` = image with size control

## Lists and tables

- `-` = unordered list
- `1.` = ordered list

## Git commands

| Command                   | What it does                       |
| ------------------------- | ---------------------------------- |
| `git init`                | Initialize a new local repository  |
| `git status`              | Check the state of your files      |
| `git add .`               | Stage all changes                  |
| `git add filename`        | Stage a specific file              |
| `git commit -m "message"` | Save a snapshot with a description |
| `git push`                | Upload to GitHub                   |
| `git pull`                | Download changes from GitHub       |
| `git log --oneline`       | See commit history                 |

## Git branches

A branch lets you split from the main line of development and work
independently without affecting the main codebase.

| Command                      | What it does                         |
| ---------------------------- | ------------------------------------ |
| `git switch -c <branchname>` | Create a new branch and switch to it |
| `git switch <branchname>`    | Switch to an existing branch         |
| `git branch`                 | List local branches                  |
| `git branch -a`              | List all branches (local and remote) |
| `git branch -d <branchname>` | Delete a branch                      |

## Pull requests (PR)

A PR is a request to merge one branch into another. Other developers
review the code, suggest changes, and approve before merging.

### Basic PR workflow

1. `git switch -c <branchname>` — create and switch to a new branch
2. Make your changes and commit them
3. `git push -u origin <branchname>` — push the branch to GitHub
4. Create a pull request on GitHub
5. Share with your team for review
6. Implement feedback, push again if needed
7. Merge the pull request into main
8. `git checkout main` then `git pull` — sync your local machine
9. Delete the branch on GitHub and locally

## File states in Git

1. **Untracked** — Git doesn't know about the file yet
2. **Staged** — ready to be committed
3. **Committed** — saved in Git history
