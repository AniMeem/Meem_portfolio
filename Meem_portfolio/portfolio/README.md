# My Portfolio Website

A simple portfolio website for a CSE graduate. Built with HTML and CSS only.

## Project Structure

```
portfolio/
├── index.html      # Home page
├── about.html      # About me page
├── projects.html   # Projects showcase
├── contact.html    # Contact information
├── css/
│   └── style.css   # All styles
└── README.md       # This file
```

## How to Customize

1. Replace "Your Name" with your actual name in all HTML files
2. Update contact information in contact.html
3. Add your education details in about.html
4. Add your real projects in projects.html
5. Change colors in css/style.css (look for :root variables)

---

## Git Practice Guide

### Step 1: Initialize Git Repository

```bash
cd /home/mahathir/Downloads/portfolio
git init
```

### Step 2: Configure Git (First time only)

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 3: First Commit

```bash
git add .
git commit -m "Initial commit: Add portfolio website"
```

### Step 4: Create GitHub Repository

1. Go to https://github.com
2. Click "New repository"
3. Name it "portfolio" (or any name you like)
4. Do NOT initialize with README
5. Click "Create repository"

### Step 5: Connect to GitHub

```bash
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

### Step 6: Practice Making Changes

Try these exercises:

**Exercise 1: Update your name**
```bash
# Edit index.html - change "Your Name" to your real name
git add index.html
git commit -m "Update name on home page"
git push
```

**Exercise 2: Add your education**
```bash
# Edit about.html - add your university details
git add about.html
git commit -m "Add education information"
git push
```

**Exercise 3: Change website colors**
```bash
# Edit css/style.css - change --primary-color
git add css/style.css
git commit -m "Change primary color to purple"
git push
```

### Useful Git Commands

| Command | Description |
|---------|-------------|
| git status | See what files changed |
| git add <file> | Stage a file for commit |
| git add . | Stage all changed files |
| git commit -m "message" | Commit with a message |
| git push | Upload to GitHub |
| git pull | Download from GitHub |
| git log | See commit history |
| git diff | See what changed |

### Branching Practice

```bash
# Create a new branch
git checkout -b feature/add-photo

# Make changes, then commit
git add .
git commit -m "Add profile photo"

# Switch back to main
git checkout main

# Merge the branch
git merge feature/add-photo

# Push to GitHub
git push
```

---

## Hosting on GitHub Pages (Free!)

1. Push your code to GitHub
2. Go to repository Settings
3. Click "Pages" in sidebar
4. Select "main" branch
5. Click Save
6. Your site will be live at: https://YOUR_USERNAME.github.io/portfolio

---

Good luck with your portfolio!
