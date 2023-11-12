## 1. Initialize and Configure Git

### Initialize a New Git Repository

```bash
git init
```

- Initializes a new Git repository in the current directory.

### Configure Global Git User

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

- Sets your global Git username and email.

---

## 2. Add and Commit Changes

### Add Files to Staging Area

```bash
git add .
```

- Adds all changes in the working directory to the staging area.

### Commit Changes

```bash
git commit -m "Initial commit"
```

- Commits the changes in the staging area with a descriptive message.

---

## 3. Create a Remote Repository

### Create a New Repository on GitHub/GitLab/Bitbucket

- Go to your preferred platform (GitHub, GitLab, Bitbucket) and create a new repository.

---

### 4. Link Local Repository to Remote

```bash
git remote add origin <repository_url>
```

- Links your local Git repository to the remote repository.

---

### 5. Push to Remote Repository

```bash
git push -u origin master
```

- Pushes the committed changes to the master branch of the remote repository.

---

## Daily Git Commands

### 1. Check Repository Status

```bash
git status
```

- Displays the status of your working directory, showing changes and untracked files.

### 2. Pull Latest Changes

```bash
git pull origin master
```

- Fetches and merges the latest changes from the remote repository into your local master branch.

### 3. Create a New Branch

```bash
git branch <branch_name>
git checkout <branch_name>
```

- Creates and switches to a new branch.

### 4. Commit Changes to Branch

```bash
git add .
git commit -m "Your commit message"
```

- Commits changes to the current branch.

### 5. Push Branch to Remote

```bash
git push origin <branch_name>
```

- Pushes the committed changes in the branch to the remote repository.

---


