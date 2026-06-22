# 🚀 Step-by-Step GitHub Deployment Guide

Follow these steps to push your IBM Plex Glyph Viewer to GitHub and deploy it with GitHub Pages.

## Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name:** `plex-glyph-viewer` (or any name you prefer)
   - **Description:** "IBM Carbon Design System compliant Plex font glyph viewer"
   - **Visibility:** Public (required for free GitHub Pages)
   - ⚠️ **DO NOT** check "Add a README file"
   - ⚠️ **DO NOT** check "Add .gitignore"
   - ⚠️ **DO NOT** choose a license
5. Click **"Create repository"**

## Step 2: Copy Your Repository URL

After creating the repository, GitHub will show you a page with setup instructions. You'll see a URL that looks like:
```
https://github.com/YOUR_USERNAME/plex-glyph-viewer.git
```

Copy this URL - you'll need it in the next step.

## Step 3: Push Your Code

Open Terminal and run these commands one at a time:

### Navigate to your project directory:
```bash
cd /Users/peternelson/Desktop/plex-glyph-viewer
```

### Add your GitHub repository as the remote origin:
Replace `YOUR_USERNAME` with your actual GitHub username:
```bash
git remote add origin https://github.com/YOUR_USERNAME/plex-glyph-viewer.git
```

### Push your code to GitHub:
```bash
git push -u origin main
```

You may be prompted to enter your GitHub credentials:
- **Username:** Your GitHub username
- **Password:** Use a Personal Access Token (not your GitHub password)

### If you need a Personal Access Token:
1. Go to GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Click "Generate new token (classic)"
3. Give it a name like "plex-glyph-viewer"
4. Select scopes: check "repo"
5. Click "Generate token"
6. Copy the token and use it as your password when pushing

## Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top menu)
3. Click **"Pages"** (left sidebar)
4. Under "Source":
   - Select **"Deploy from a branch"**
   - Branch: **"main"**
   - Folder: **"/ (root)"**
5. Click **"Save"**
6. Wait 1-2 minutes for deployment

Your site will be live at:
```
https://YOUR_USERNAME.github.io/plex-glyph-viewer/
```

## Step 5: Update the README

Once your site is live, update the README with your actual URL:

1. Edit `README.md`
2. Replace `yourusername` with your actual GitHub username in the live demo link
3. Commit and push the change:
```bash
git add README.md
git commit -m "Update live demo URL"
git push
```

## Troubleshooting

### "Permission denied" error
- Make sure you're using a Personal Access Token, not your password
- Check that your token has "repo" permissions

### "Repository not found" error
- Double-check the repository URL
- Make sure the repository exists on GitHub
- Verify you're using the correct username

### GitHub Pages not working
- Wait a few minutes after enabling Pages
- Check that your repository is public
- Verify the branch and folder settings are correct

## Quick Reference Commands

```bash
# Check current status
git status

# View commit history
git log --oneline

# Check remote URL
git remote -v

# Change remote URL if needed
git remote set-url origin https://github.com/YOUR_USERNAME/plex-glyph-viewer.git
```

## Need Help?

- [GitHub Docs: Creating a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
- [GitHub Docs: GitHub Pages](https://docs.github.com/en/pages)
- [GitHub Docs: Personal Access Tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

---

Good luck! 🎉