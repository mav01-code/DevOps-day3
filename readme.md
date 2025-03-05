# Git Commands - DevOps-Day3

This document lists the Git commands used while working on the `DevOps-Day3` project.

---

## 1. Initial Setup
```bash
ls -la                    # List all files and directories  
mkdir git_lab             # Create a new directory named 'git_lab'  
cd git_lab                # Move into the 'git_lab' directory  
git init                  # Initialize a new Git repository  
```

---

## 2. SSH Key Generation & Setup
```bash
ssh-keygen                # Generate a new SSH key pair  
ls -la ~/.ssh             # Verify SSH key exists  
cat ~/.ssh/id_ed25519.pub # Display the public SSH key (to add it to GitHub)  
```

---

## 3. Working with the Repository
```bash
cd git_lab                
git branch                # Check the current branch  
git status                # Check the status of the repository  
```

---

## 4. Cloning and Remote Setup
```bash
git clone git@github.com:mav01-code/DevOps-day3.git  # Clone the repository  
git remote -v               # Verify remote repository  
git remote add origin git@github.com:mav01-code/DevOps-day3.git  # Add remote manually  
```

---

## 5. Branch Management
```bash
git branch                 # List all branches  
git branch main            # Create 'main' branch  
git branch master          # Create 'master' branch  
git checkout main          # Switch to 'main' branch  
git merge master           # Merge 'master' into 'main'  
git branch cse             # Create 'cse' branch  
git checkout cse           # Switch to 'cse' branch  
git merge main             # Merge 'main' into 'cse'  
git merge cse              # Merge 'cse' into 'main'  
```

---

## 6. Tracking and Committing Changes
```bash
ls                         # List files in the directory  
git add .                  # Stage all changes  
git status                 # Check status of staged files  
git commit -m "File1"      # Commit changes with message  
nano manual                # Open 'manual' file for editing  
git add .                  # Stage changes  
git commit -m "Added manual" # Commit with a descriptive message  
```

---

## 7. Pushing Changes to Remote Repository
```bash
git push -u origin main     # Push changes to 'main' branch  
git push -f origin main     # Force push changes to 'main' branch  
git push -f origin master   # Force push changes to 'master' branch  
git push -u origin main     # Push changes after merging  
```

---

## 8. Checking Repository History
```bash
git log                     # View commit history  
```

---

This README serves as a reference for Git commands used during the `DevOps-Day3` project. 🚀
