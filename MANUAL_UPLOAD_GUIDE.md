# 📤 Manual Upload to GitHub (No Command Line)

If you prefer not to use the command line, you can upload your files directly through GitHub's web interface.

## Step 1: Create a New Repository on GitHub

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. Fill in:
   - **Repository name:** `plex-glyph-viewer`
   - **Description:** "IBM Carbon Design System compliant Plex font glyph viewer"
   - **Visibility:** ✅ Public (required for free GitHub Pages)
   - ⚠️ **DO NOT** check any boxes (no README, .gitignore, or license)
5. Click **"Create repository"**

## Step 2: Upload Your Files

After creating the repository, you'll see a page with setup instructions. Look for the section that says **"uploading an existing file"** or follow these steps:

### Option A: Drag and Drop
1. On your repository page, click **"uploading an existing file"** link
2. Open Finder and navigate to: `/Users/peternelson/Desktop/plex-glyph-viewer/`
3. Select ALL files:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `DEPLOYMENT_GUIDE.md`
   - `MANUAL_UPLOAD_GUIDE.md`
   - `.gitignore`
4. Drag and drop them into the GitHub upload area
5. Scroll down to "Commit changes"
6. In the commit message box, type: `Initial commit: IBM Plex Glyph Viewer`
7. Click **"Commit changes"**

### Option B: Add Files One by One
1. Click **"Add file"** → **"Upload files"**
2. Click **"choose your files"**
3. Navigate to `/Users/peternelson/Desktop/plex-glyph-viewer/`
4. Select all files (Cmd+A)
5. Click **"Open"**
6. Scroll down and click **"Commit changes"**

## Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu bar)
2. Scroll down the left sidebar and click **"Pages"**
3. Under "Build and deployment":
   - **Source:** Select **"Deploy from a branch"**
   - **Branch:** Select **"main"** (or "master")
   - **Folder:** Select **"/ (root)"**
4. Click **"Save"**
5. Wait 1-2 minutes

A green box will appear with your site URL:
```
Your site is live at https://YOUR_USERNAME.github.io/plex-glyph-viewer/
```

## Step 4: Update the README (Optional)

1. In your repository, click on `README.md`
2. Click the pencil icon (✏️) to edit
3. Find the line with `[View Live Demo](https://yourusername.github.io/plex-glyph-viewer/)`
4. Replace `yourusername` with your actual GitHub username
5. Scroll down and click **"Commit changes"**
6. Click **"Commit changes"** again in the popup

## Step 5: View Your Live Site! 🎉

Click on the GitHub Pages URL or visit:
```
https://YOUR_USERNAME.github.io/plex-glyph-viewer/
```

## Important Notes

### About .gitignore
The `.gitignore` file might not show up in Finder because it starts with a dot (hidden file). To see it:
- In Finder, press: **Cmd + Shift + . (period)**
- This will show hidden files
- Now you can select and upload `.gitignore` too

### If You Make Changes Later
1. Go to your repository on GitHub
2. Click on the file you want to edit
3. Click the pencil icon (✏️)
4. Make your changes
5. Scroll down and click **"Commit changes"**
6. Your GitHub Pages site will automatically update in 1-2 minutes

## Troubleshooting

### "Your site is having problems building"
- Make sure `index.html` is in the root folder (not in a subfolder)
- Wait a few minutes and refresh the Pages settings

### Can't see .gitignore file
- Press **Cmd + Shift + .** in Finder to show hidden files
- Or just skip it - it's not critical for the site to work

### Site shows 404 error
- Wait 2-3 minutes after enabling Pages
- Make sure the repository is Public
- Check that `index.html` is in the root folder

## Alternative: GitHub Desktop App

If you want a middle ground between command line and manual upload:

1. Download [GitHub Desktop](https://desktop.github.com/)
2. Install and sign in
3. Click **"Add"** → **"Add Existing Repository"**
4. Browse to `/Users/peternelson/Desktop/plex-glyph-viewer/`
5. Click **"Publish repository"**
6. Make sure "Keep this code private" is **unchecked**
7. Click **"Publish repository"**

Then follow Step 3 above to enable GitHub Pages.

---

That's it! No command line needed. 🎉