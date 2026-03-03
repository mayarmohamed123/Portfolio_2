# 🚀 Git Repository Setup Guide

Follow these steps to add your project to a new GitHub (or GitLab/Bitbucket) repository.

## 1️⃣ Initialize Local Repository
Open your terminal in the `Portfolio_2` directory and run:
```bash
git init
```

## 2️⃣ Add Your Files
Stage all your project files for the first commit:
```bash
git add .
```

## 3️⃣ Create Initial Commit
Commit the staged files with a descriptive message:
```bash
git commit -m "Initial commit: Professional portfolio template with README"
```

## 4️⃣ Create a Remote Repository
1. Go to Your [GitHub Account](https://github.com/new).
2. Create a new repository (e.g., `Daniels-Portfolio`).
3. Leave it empty (do **not** initialize with README or License).

## 5️⃣ Link Local to Remote
Copy the SSH or HTTPS URL from your new GitHub repository and run:
```bash
git remote add origin <your-repo-url>
```
*Example:* `git remote add origin https://github.com/username/Daniels-Portfolio.git`

## 6️⃣ Set Main Branch & Push
Set the default branch to `main` and push your code:
```bash
git branch -M main
git push -u origin main
```

---
### ✅ Success!
Your project is now live on your repository. Any future changes can be updated with:
```bash
git add .
git commit -m "Describe your changes"
git push
```
