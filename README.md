# How-to-Push-Code-to-Git-and-GitHub
If you are learning programming, DevOps, or open-source contribution, knowing how to push code to GitHub is essential. 
This file is beginner-friendly and works on Windows, macOS, and Linux.

## What are Git and GitHub?
Git → a version control system that tracks changes in your code
GitHub → a cloud platform where Git repositories are stored and shared

### Think of:
Git = saves versions locally
GitHub = backup + collaboration over the internet

## Prerequisites
Installed Git
Have a GitHub account
Have a project folder on your computer

## Step 1: Configure Git (First Time Only)
Open Terminal / Command Prompt and run:
```
git config --global user.name "Your Name"
git config --global user.email "your@email.com" 
```
This identity appears in your commits.

## Step 2: Go to your project folder
cd path/to/your/project
Example:
cd Desktop/my-project

## Step 3: Initialize Git in the folder
```git init```
Now your folder becomes a Git repository.

## Step 4: Check Git status
```git status```

<img width="850" height="328" alt="Screenshot (239)" src="https://github.com/user-attachments/assets/2d7bdf4d-f86c-4539-ba34-f1e89a5d869c" />

This shows new, modified, or tracked files.

## Step 5: Add files to staging area
```git add .```

<img width="627" height="314" alt="Screenshot (240)" src="https://github.com/user-attachments/assets/9df8bb0f-aa75-4050-9954-8626e9d83481" />

. means add all files
(You can add single files too.)

## Step 6: Commit your code

```git commit -m "Initial commit"```

<img width="1239" height="546" alt="Screenshot (241)" src="https://github.com/user-attachments/assets/3b12c23a-590a-4deb-997a-42194505e6b2" />

A commit = a saved version of your code.

## Step 7: Create a repository on GitHub
Go to GitHub → New Repository
enter repo name
choose public/private
click Create repository
important --> If your local project already has files, do NOT initialize with README on GitHub.

## Step 8: Copy repository URL
https://github.com/username/repository.git

## Step 9: Add remote origin

```git remote add origin https://github.com/username/repository.git```

<img width="1366" height="198" alt="Screenshot (242)" src="https://github.com/user-attachments/assets/9373ae63-2bee-46ff-96dd-2e585acbd1a1" />

## Step 10: Push code to GitHub (first push)
```
git branch -M main
git push -u origin main
```

### If git push origin main asks for username & password and your password fails — this is expected.
### GitHub has removed password authentication for Git operations.
### Use Personal Access Token (PAT)

GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic) -> Generate new token -> Select repo permission -> Copy the token

<img width="1366" height="768" alt="Screenshot (246)" src="https://github.com/user-attachments/assets/bdac6626-2658-4859-b2b2-bc60e7464a8c" />

# NOW IF YOU TRY 

<img width="1060" height="446" alt="Screenshot (249)" src="https://github.com/user-attachments/assets/3942e3ea-00ff-47ab-87ee-1e6cae6dae5a" />

Congratulations !!
Your project is now live on GitHub!
