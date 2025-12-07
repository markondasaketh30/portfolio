# 🚀 Quick GitHub Pages Deployment Guide

## Step 1: Create Repository (Manual)

1. Go to [github.com/markondasaketh30](https://github.com/markondasaketh30)
2. Click **"New"** button (green, top right)
3. **Repository name**: `portfolio`
4. **Description**: `Professional Cyber Security Analyst Portfolio`
5. **Public** (selected)
6. **Don't** check "Add a README file"
7. Click **"Create repository"**

## Step 2: Push Files

Run these commands in your terminal:

```bash
cd /home/saketh/opencode/portfolio
git remote set-url origin https://markondasaketh30:YOUR_TOKEN@github.com/markondasaketh30/portfolio.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your new repository: https://github.com/markondasaketh30/portfolio
2. Click **Settings** tab
3. Click **Pages** in left menu
4. Source: "Deploy from a branch"
5. Branch: `main` → `/ (root)`
6. Click **Save**

## Step 4: Wait for Deployment

- GitHub will take 1-2 minutes to deploy
- Your site will be live at: https://markondasaketh30.github.io/portfolio

## 📁 Files Ready to Deploy

✅ index.html - Main portfolio page
✅ styles.css - Modern responsive styling
✅ script.js - Interactive features
✅ README.md - Documentation
✅ .gitignore - Git ignore file

## 🎯 Features Included

- Responsive design for all devices
- Modern animations and effects
- Contact form with validation
- Social media links
- Project showcase
- Skills section

Once you create the repository, the files are ready to push immediately!
