### 1. Clone Repository

```bash
git clone <repository_url>
```

- Clones the repository from the specified URL to your local machine.

### 2. Check Repository Status

```bash
git status
```

- Displays the status of your working directory, showing changes and untracked files.

### 3. Create a New Branch

```bash
git branch <branch_name>
```

- Creates a new branch with the specified name.

### 4. Switch to a Branch

```bash
git checkout <branch_name>
```

- Switches to the specified branch.

### 5. Create and Switch to a New Branch

```bash
git checkout -b <new_branch_name>
```

- Creates a new branch and switches to it in a single command.

### 6. Commit Changes

```bash
git add .
git commit -m "Your commit message"
```

- Adds all changes to the staging area and commits them with a descriptive message.

### 7. Pull Latest Changes

```bash
git pull origin <branch_name>
```

- Fetches and merges the latest changes from the remote repository into your local branch.

### 8. Push Commits to Remote Repository

```bash
git push origin <branch_name>
```

- Pushes your local commits to the remote repository on the specified branch.

### 9. Merge Branch

```bash
git merge <branch_name>
```

- Merges the specified branch into the current branch.

### 10. View Commit History

```bash
git log
```

- Displays a log of all commits, showing commit messages, authors, and commit dates.

### 11. Configure Global Git User

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

- Sets your global Git username and email.

### 12. Resolve Merge Conflicts

Handle merge conflicts by editing the conflicted files and then:

```bash
git add <conflicted_file>
git commit -m "Merge conflict resolution"
```

- Marks the conflicted file as resolved and commits the changes.

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

Feel free to customize this README based on your project's needs.

```

Adjust placeholders like `<repository_url>`, `<branch_name>`, and `<new_branch_name>` with your actual values. Customize the explanations and add any other commands relevant to your project.
```
