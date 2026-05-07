# ?? GitHub & Cursor Setup Journey

This repository documents my learning journey setting up GitHub, Git, Cursor IDE, and Windows PowerShell for local development and version control workflow.

The objective of this setup was to learn how to:
- Install and configure development tools
- Connect GitHub with Cursor IDE
- Clone repositories locally
- Create and edit markdown files
- Push and commit files from local machine to GitHub

---

# ??? Tools Installed

| Tool | Description |
|---|---|
| Cursor IDE | AI powered code editor |
| Git | Version control system |
| GitHub | Repository hosting platform |
| Windows PowerShell | Command line interface for Git commands |

---

# ? Steps Completed

## 1. Installed Cursor IDE
- Downloaded and installed Cursor IDE
- Signed up for a free Cursor account

---

## 2. Signed Up for GitHub
- Created a GitHub account
- Learned repository setup basics

---

## 3. Installed Git on Local Machine
- Downloaded Git for Windows
- Installed Git locally on PC

---

## 4. Configured Git via Windows PowerShell

Verified Git installation:

git --version

Configured Git username and email:

git config --global user.name "Your Name"
git config --global user.email "your@email.com"

---

## 5. Created New Repository on GitHub
- Created a new GitHub repository
- Configured repository settings

---

## 6. Cloned Git Repository to Local Machine

Used PowerShell command:

git clone https://github.com/USERNAME/REPOSITORY.git

Moved into repository folder:

cd REPOSITORY_NAME

---

## 7. Created Test Markdown File

Created a sample markdown file named Test1.md to understand how markdown files are created and managed locally before working on the actual README.md file.

Used PowerShell command:

New-Item Test1.md

Added sample markdown content into the file to test formatting and Git workflow.

Example content:

# Hello World ??

I am new to GitHub and learning Git workflow.

---

## 8. Created README.md File

Created README.md locally:

New-Item README.md

---

## 9. Edited README.md Using Cursor IDE
- Opened repository folder in Cursor
- Added markdown content
- Saved changes locally

---

## 10. Pushed README.md to GitHub

Used Git commands in PowerShell:

git add .
git commit -m "Initial README setup"
git push origin main

Successfully uploaded local README.md into GitHub repository.

---

# ?? Issues Faced & Solutions

## 1. Integrating Cursor & GitHub

### Issue
Cursor integration with GitHub initially failed because the server was busy.

### Solution
Retried the authentication process multiple times until successful.

---

## 2. Figuring Out How to Clone Git Repository

### Issue
Initially unsure how to clone GitHub repositories into local machine using PowerShell.

### Solution
Checked Git documentation, Git knowledge base, and YouTube tutorials to understand the workflow.

---

## 3. Creating, Pushing & Committing README.md via Cursor & PowerShell

### Issue
Had difficulty understanding the Git workflow for:
- Creating files
- Staging changes
- Committing changes
- Pushing files to GitHub

### Solution
Used Cursor AI assistance together with YouTube tutorials to learn the full workflow step by step.

---

## 4. Figuring Out How to Write README.md Based on GitHub Style

### Issue
Initially unsure how to structure and write a professional README.md following common GitHub documentation style and formatting.

### Solution
Listed down:
- Project requirements
- Thought process
- Workflow steps
- Problems faced
- Solutions implemented

Then used Cursor AI assistance to rewrite and structure the content into proper GitHub README.md format with markdown styling and documentation structure.

---

# ?? Key Learning Outcomes

Through this setup process, I learned:
- Basic Git workflow
- Repository management
- Local development environment setup
- GitHub integration
- Markdown editing
- Using PowerShell for Git operations
- Using AI assisted IDE tools like Cursor

---

