Sure! Here's the complete Git notes content as a **single Markdown (.md) file**. You can save it with a `.md` extension (e.g., `git-notes.md`).

---

```markdown
# 📘 Git Notes

A concise guide to essential Git commands and workflows.

---

## 🔧 Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --list
```

---

## 📁 Repository Setup

```bash
git init                         # Initialize new git repository
git clone <repo-url>            # Clone remote repository
```

---

## 📌 Common Git Commands

```bash
git status                      # Check status of files
git add <file>                  # Stage a specific file
git add .                       # Stage all changes
git commit -m "Commit message" # Commit changes
git log                         # Show commit history
```

---

## 🔁 Branching and Merging

```bash
git branch                      # List branches
git branch <branch-name>       # Create new branch
git checkout <branch-name>     # Switch to branch
git checkout -b <branch-name>  # Create and switch
git merge <branch-name>        # Merge into current branch
git branch -d <branch-name>    # Delete branch
```

---

## 🌐 Remote Repositories

```bash
git remote -v                   # List remote URLs
git remote add origin <url>    # Add remote repository
git push -u origin main         # Push changes & set upstream
git pull origin main            # Pull changes
```

---

## 🧹 Undo & Reset

```bash
git reset <file>               # Unstage file
git checkout -- <file>         # Discard file changes
git revert <commit>            # Revert a commit
git reset --hard <commit>      # Reset to previous commit (DANGER!)
```

---

## 📂 Stashing Work

```bash
git stash                      # Stash changes
git stash list                 # List stashes
git stash apply                # Apply latest stash
git stash drop                 # Drop stash
```

---

## 🎯 Tagging

```bash
git tag v1.0                   # Create tag
git tag                        # List tags
git push origin v1.0          # Push tag
```

---

## 🧠 Useful Tips

- `.gitignore` file is used to ignore files/directories.
- `git diff` shows file changes not staged.
- `git fetch` downloads changes, but doesn't merge.
- Always pull before pushing to avoid conflicts.

---

## 📚 Resources

- [Official Git Docs](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
```

---

Would you like me to generate a downloadable `.md` file for this too?
