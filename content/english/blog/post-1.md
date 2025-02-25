---
title: "How to use Git with GitHub."
meta_title: "use Git with GitHub"
description: "This guide covered the basics of Git and GitHub to help you track changes, collaborate, and manage versions efficiently.  "
date: 2025-02-25T00:00:00Z
image: "/images/image-placeholder.png"
categories: ["Git", "Git Hub"]
author: "Chinmay Singh"
tags: ["Git", "Git Hub"]
draft: false
---

Here’s a simple blog post on   

---

### **Getting Started with Git and GitHub**  

Git is a powerful version control system that helps track changes in your code. GitHub allows you to store your projects remotely, collaborate with others, and manage versions effectively. This guide will help you get started with Git and GitHub.

---

## **1. Initializing a Git Repository**  
To start tracking your project with Git, navigate to your project folder and initialize a repository:

```sh
cd my-project
git init
```

This creates a hidden `.git` folder, making it a Git repository.

---

## **2. Tracking and Committing Files**  
After making changes, add them to Git’s staging area:  

```sh
git add .
```
Or add specific files:

```sh
git add filename.txt
```

Next, commit your changes with a message:  

```sh
git commit -m "Initial commit"
```

---

## **3. Configuring Git User Details**  
Set up your Git username and email (used for commits):

```sh
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

---

## **4. Cloning a GitHub Repository**  
To download an existing GitHub repository:

```sh
git clone <repo-url>
```

---

## **5. Checking Repository Status**  
View the current status of your files:

```sh
git status
```

Check the remote repository URL:

```sh
git remote -v
```

---

## **6. Syncing with GitHub**  
To fetch updates from GitHub without applying them:

```sh
git fetch origin
```

To fetch and merge updates:

```sh
git pull origin main
```

To push local changes to GitHub:

```sh
git push origin main
```

---

## **7. Working with Branches**  
To create and switch to a new branch:

```sh
git checkout -b new-feature
```

To list all branches:

```sh
git branch
```

To switch to another branch:

```sh
git checkout main
```

For newer versions of Git:

```sh
git switch main
```

---

## **8. Merging Branches**  
To merge a feature branch into the main branch:

```sh
git checkout main
git merge new-feature
```

If conflicts arise, resolve them manually, then:

```sh
git add .
git commit -m "Resolved merge conflicts"
```

---

## **9. Using GitHub Pull Requests** *(Recommended for Teams)*  
1. Push your branch to GitHub:  

   ```sh
   git push origin new-feature
   ```

2. On GitHub, go to the **Pull Requests** tab.
3. Click **"New pull request"**.
4. Select the source and target branches.
5. Click **"Create pull request"** and merge after approval.

---

### **Conclusion**  
This guide covered the basics of Git and GitHub to help you track changes, collaborate, and manage versions efficiently.  
