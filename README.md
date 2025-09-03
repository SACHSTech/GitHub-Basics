# The Basics of GitHub

Git is a **Version Control System (VCS)**. A VCS helps track changes made to files over time, so you can revisit earlier versions, understand what changed, and collaborate with others without losing work. GitHub is a cloud service that hosts Git repositories and makes them accessible anywhere with an internet connection.

## Why We Use Git
- **History:** Git records the evolution of a project. Each change is saved in a way that can be revisited or restored.  
- **Clarity:** Descriptive commit messages explain *why* changes were made.  
- **Collaboration:** Multiple people can work on the same project at once, and Git helps manage how their changes fit together.

## What Gets Stored in a Repository
A repository (often called a **repo**) is more than just a folder of files. It contains:  
- **Project files:** Code, documents, images, or anything else related to the project.  
- **Commit history:** Every saved change, along with the author, date, and message.  
- **Metadata:** Extra information Git uses to manage the project (such as commit IDs and references to contributors).  

Think of a repository as both the **current version of the project** *and* a **time machine** that can show you how it looked in the past.

## Where Work Is Stored
- **Remote Repository:** Stored in the cloud on GitHub’s servers. This is the version everyone can see and use.  
- **Local Copy (later):** Developers often clone a repo to their own computer to work offline, then sync changes back to the remote. For now, we focus on the version stored directly on GitHub.

## Commit Messages
A **commit** is a snapshot of your work at a specific point in time. Every commit requires a **commit message**.  

- Good commit messages are **short, clear, and specific.**  
- They describe what was changed and why, so that anyone looking at the history can understand.  

**Good Examples:**  
- `Added introduction section to README`  
- `Fixed typo in function description`  

**Poor Examples:**  
- `update`  
- `stuff`

## Key Terminology
- **Repository (Repo):** The container that holds a project’s files and its full history of changes.  
- **Commit:** A saved snapshot of the project at a moment in time, with a descriptive message.  
- **Fork:** A complete copy of a repository under your own GitHub account. Forking is often used when contributing to someone else’s project.  

## Basic Workflow for Git Browser Editing
1. Make a **meaningful change** to a file (e.g., add content, edit text).  
2. Write a **descriptive commit message** that explains what you changed.  
3. **Commit** the change to save it to the repository’s history.  

Over time, this creates a sequence of commits that shows the project’s development step by step.
