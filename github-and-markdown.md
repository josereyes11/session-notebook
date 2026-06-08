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

| Command                          | What it does                      |
| -------------------------------- | --------------------------------- |
| `git checkout -b branch-name`    | Create and switch to a new branch |
| `git branch`                     | List all branches                 |
| `git push -u origin branch-name` | Push a new branch to GitHub       |

## File states in Git

1. **Untracked** — Git doesn't know about the file yet
2. **Staged** — ready to be committed
3. **Committed** — saved in Git history
