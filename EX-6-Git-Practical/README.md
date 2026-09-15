# EX-6: Git and GitHub Practical

**Student:** Gurjot Singh  
**GitHub:** Gurjot3019

## Objective
To install Git, configure Git, initialize a local repository, create and commit a file, connect the repository with GitHub, and push the project to the `main` branch.

## Procedure

1. Install Git for Windows from the official Git website.
2. Verify installation:
   `git --version`
3. Configure Git user details:
   `git config --global user.name "Gurjot Singh"`
   `git config --global user.email "gurjotsingh2644@gmail.com"`
4. Create and enter a project directory:
   `mkdir myproject`
   `cd myproject`
5. Initialize the repository:
   `git init`
6. Create a sample file:
   `echo "Hello Git" > readme.txt`
7. Add the file to the staging area:
   `git add readme.txt`
8. Commit the file:
   `git commit -m "Initial commit with readme"`
9. View commit history:
   `git log`
10. Connect the local repository to the GitHub repository using `git remote add origin <repository-url>`.
11. Rename the branch to `main`:
    `git branch -M main`
12. Push the project:
    `git push -u origin main`

## Result
The Git repository is initialized, the sample file is committed, and the project is prepared for synchronization with GitHub.

> Note: Git installation and local terminal commands must be executed on the student's computer. The GitHub-connected portion of this practical is maintained in this repository.