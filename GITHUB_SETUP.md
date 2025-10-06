# 🚀 How to Publish This to GitHub

## Quick Setup (5 minutes)

### Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the **"+"** icon (top right) → **"New repository"**
3. Repository name: `benefact-impact-calculator` (or your choice)
4. Description: `Interactive calculator showing how insurance creates community impact`
5. Choose **Public** (so it can be seen in your portfolio)
6. **Don't** initialize with README (we already have one)
7. Click **"Create repository"**

### Step 2: Publish Your Files

**Option A: Upload via Web Interface (Easiest)**

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop these three files:
   - `benefact-impact-calculator.html`
   - `README.md`
   - `LICENSE`
3. Commit message: `Initial commit - Impact Calculator`
4. Click **"Commit changes"**

Done! Your project is now live on GitHub.

**Option B: Use Git Command Line (If you have Git installed)**

```bash
# Navigate to the folder with your files
cd /path/to/your/files

# Initialize git repository
git init

# Add all files
git add benefact-impact-calculator.html README.md LICENSE

# Make your first commit
git commit -m "Initial commit - Impact Calculator"

# Add your GitHub repository as remote
# (Replace YOUR-USERNAME with your actual GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/benefact-impact-calculator.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages (Make it Live on the Web!)

1. Go to your repository on GitHub
2. Click **"Settings"** (top right)
3. Scroll down to **"Pages"** (left sidebar)
4. Under "Source", select **"main"** branch
5. Click **"Save"**
6. Wait ~2 minutes
7. Your site will be live at: `https://YOUR-USERNAME.github.io/benefact-impact-calculator/benefact-impact-calculator.html`

🎉 **Now you have a live demo you can share!**

### Step 4: Add to Your CV/Portfolio

You can now link to:
- **Repository**: `https://github.com/YOUR-USERNAME/benefact-impact-calculator`
- **Live Demo**: `https://YOUR-USERNAME.github.io/benefact-impact-calculator/benefact-impact-calculator.html`

---

## Optional: Clean URL Setup

To make the URL cleaner (remove the `.html` from the end):

1. Rename `benefact-impact-calculator.html` to `index.html`
2. Upload/push the change
3. Your live demo will be: `https://YOUR-USERNAME.github.io/benefact-impact-calculator/`

---

## Need Help?

**Common Issues:**

1. **"Permission denied"** when pushing
   - Make sure you're logged into GitHub
   - You may need to set up SSH keys or use a Personal Access Token

2. **GitHub Pages not working**
   - Wait 5-10 minutes (it can take time)
   - Check Settings → Pages to see if there are errors

3. **Can't find Git commands**
   - You may need to install Git: https://git-scm.com/downloads
   - Or just use the web upload method (Option A)

---

## Files Location

All files are in: `/mnt/user-data/outputs/`

- `benefact-impact-calculator.html` - The main calculator
- `README.md` - Documentation
- `LICENSE` - MIT license
- `GITHUB_SETUP.md` - This file

Download them all and follow the steps above!
