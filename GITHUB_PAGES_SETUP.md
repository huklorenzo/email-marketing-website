# GitHub Pages Setup Guide

## Step 1: Make Repository Public

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down to **"Danger Zone"** section
4. Click **"Change visibility"**
5. Select **"Make public"**
6. Type your repository name to confirm
7. Click **"I understand, change repository visibility"**

## Step 2: Enable GitHub Pages

1. Still in **Settings**, scroll to **"Pages"** in the left sidebar
2. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
3. Click **"Save"**

## Step 3: Access Your Site

- Your site will be live at:
  `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`
  
- Example:
  If your username is `huklorenzo` and repo is `email-marketing-portfolio`:
  `https://huklorenzo.github.io/email-marketing-portfolio/`

## Step 4: Wait for Deployment

- GitHub Pages usually takes 1-2 minutes to deploy
- You'll see a green checkmark when it's ready
- Refresh your site URL to see it live

## Troubleshooting

**If your site shows 404:**
- Wait a few minutes (first deployment can take 5-10 minutes)
- Check that the repository is **Public**
- Verify the branch is set to **main** in Pages settings
- Make sure `index.html` is in the root directory

**If you want a custom domain:**
- In Pages settings, add your custom domain
- Update your DNS records as instructed

## Quick Commands to Push Your Code

If you haven't pushed yet:

```bash
# Add remote (replace with your actual repo URL)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then follow Steps 1-3 above!
