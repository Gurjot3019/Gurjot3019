# EX-9 — Git and GitHub Practical

## Aim
To install and configure Git, initialize a local Git repository, create a sample file, stage and commit changes, view commit history, create a GitHub repository, connect the local repository to GitHub, and push the project to the remote repository.

## Learning Outcomes
- Install and configure Git on a computer.
- Understand local Git repositories and version control.
- Add files to the staging area and commit changes.
- View commit history using Git.
- Connect a local repository with GitHub.
- Push project files to a remote GitHub repository.

## Procedure

### 1. Install Git
Download Git from the official website:
https://git-scm.com/downloads

Run the installer and follow the on-screen instructions.

### 2. Verify Git installation
Open Git Bash or Command Prompt:

```bash
git --version
```

### 3. Configure Git
Replace the values with your own details:

```bash
git config --global user.name "Gurjot Singh"
git config --global user.email "your-email@example.com"
```

### 4. Create a project directory

```bash
mkdir myproject
cd myproject
```

### 5. Initialize a Git repository

```bash
git init
```

Expected result:

```
Initialized empty Git repository
```

### 6. Create a sample file

```bash
echo "Hello Git" > readme.txt
```

### 7. Add the file to the staging area

```bash
git add readme.txt
```

### 8. Commit the file

```bash
git commit -m "Initial commit with readme"
```

### 9. View commit history

```bash
git log
```

### 10. Connect the local repository to GitHub

After creating the GitHub repository, copy its HTTPS URL and run:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Check the remote:

```bash
git remote -v
```

### 11. Rename the branch to main

```bash
git branch -M main
```

### 12. Push the project to GitHub

```bash
git push -u origin main
```

Git may ask you to complete authentication in your browser.

## Result
The Git repository was initialized successfully, a sample file was committed, the local repository was connected to GitHub, and the project was pushed to the remote repository.

## Commands Used

| Command | Purpose |
|---|---|
| `git --version` | Check Git installation |
| `git config` | Configure Git user details |
| `mkdir` | Create a directory |
| `cd` | Open the project directory |
| `git init` | Initialize a Git repository |
| `git add` | Stage files |
| `git commit` | Save a version of the project |
| `git log` | View commit history |
| `git remote add origin` | Connect GitHub remote |
| `git branch -M main` | Rename the branch to main |
| `git push -u origin main` | Upload changes to GitHub |
