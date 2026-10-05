# DSA & Problem Solving Portfolio

## 🚀 Git Setup & Workflow Guide

### 1. Initialize & Link a New Repository

Run these commands inside your project folder to set up Git and connect it to GitHub:

```bash
# Navigate to your project folder
cd path/to/your-folder

# Initialize Git
git init

# Add all files to staging
git add .

# Create initial commit
git commit -m "Initial commit"

# Rename branch to main
git branch -M main

# Link to your remote GitHub repository
git remote add origin [https://github.com/](https://github.com/)<your-username>/<repo-name>.git

# Push code to GitHub
git push -u origin main

```

### 2. Daily Workflow( Adding New Solutions)

```bash
# Check modified or untracked files
git status

# Stage all new and modified files
git add .

# Commit changes with a descriptive message
git commit -m "Add <problem-name> solution"

# Push updates to GitHub
git push

```

### 3. Useful Commands

```bash
 # Check commit history
git log --oneline

 # Check remote URL
git remote -v

 # Pull latest changes from remote
git pull origin main

```

### 4. Steps to retrieve a repository from GitHub back onto local machine

```bash
# move to storage repository
cd ~/Documents

# Clone the repository using your GitHub URL
git clone https://github.com/RamavathPavan-181611/dsa-solutions.git

# Step inside the newly downloaded directory
cd dsa-solutions



```
