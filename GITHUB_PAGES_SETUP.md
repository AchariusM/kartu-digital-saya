# GitHub Pages Setup - Step by Step Guide

Complete guide to deploy your portfolio using GitHub Pages.

---

## **Step 1: Navigate to Repository Settings**

1. Go to your repository: `https://github.com/AchariusM/kartu-digital-saya`
2. Click the **Settings** tab at the top right of the page
3. You should see a left sidebar menu with various options

---

## **Step 2: Find Pages Section**

1. In the left sidebar, look for **"Pages"** (usually near the bottom under "Code and automation")
2. Click on **"Pages"**
3. You're now in the GitHub Pages settings

---

## **Step 3: Configure Source**

1. Under **"Build and deployment"** section, you'll see:
   - **Source** dropdown (currently says "Deploy from a branch")

2. Make sure **"Deploy from a branch"** is selected

---

## **Step 4: Select Branch**

1. Below Source, you'll see **Branch** dropdown
2. Select **`main`** (this is where your code is)
3. Next to it, make sure folder is set to **`/ (root)`**
4. Click **"Save"** button

---

## **Step 5: Wait for Deployment**

1. After clicking Save, GitHub starts deploying your site
2. You'll see a message: *"Your site is live at..."*
3. Wait 1-3 minutes for full deployment
4. The page will refresh and show your site URL

---

## **Step 6: Access Your Live Portfolio**

Your site is now live at:

### 🌐 `https://AchariusM.github.io/kartu-digital-saya`

---

## **Complete Steps with Screenshots**

### Step 1-2: Navigate to Settings → Pages
```
GitHub Repo Page
├── Click "Settings" tab
└── Click "Pages" in left sidebar
```

### Step 3-4: Configure Deployment
```
GitHub Pages Settings
├── Build and deployment
│   ├── Source: "Deploy from a branch" ✓
│   ├── Branch: "main" + "/ (root)" ✓
│   └── Click "Save"
```

### Step 5-6: Deployment Complete
```
✅ Site deployed successfully
🌐 Live at: https://AchariusM.github.io/kartu-digital-saya
```

---

## **Verify Deployment**

1. Open `https://AchariusM.github.io/kartu-digital-saya` in your browser
2. You should see:
   - Your profile image on the left
   - Your name and title
   - Navigation menu
   - All your portfolio sections

---

## **Making Updates**

After deployment, any changes you make will update automatically:

1. **Edit files locally** (in VS Code)
2. **Commit changes**: `git add .` → `git commit -m "message"`
3. **Push to GitHub**: `git push origin main`
4. **Wait 1-2 minutes** for auto-deployment
5. **Refresh your live site** to see changes

---

## **Troubleshooting**

### ❌ Site Not Showing Up

**Problem**: I can't access my site
- **Solution**: Wait 2-3 minutes (first deployment takes longer)
- **Check**: Go to Settings → Pages and verify source is set to `main` branch

### ❌ Old Content Still Showing

**Problem**: I made changes but they're not live
- **Solution**: Hard refresh browser (`Ctrl+Shift+R` or `Cmd+Shift+R`)
- **Check**: Push was successful and 2 minutes have passed

### ❌ 404 Error

**Problem**: Page not found error
- **Solution**: 
  - Check your repo is public (Settings → Change visibility)
  - Verify `index.html` is in root folder
  - Confirm Pages is enabled in Settings

---

## **Quick Reference URLs**

| What | URL |
|------|-----|
| Repository | `https://github.com/AchariusM/kartu-digital-saya` |
| Live Portfolio | `https://AchariusM.github.io/kartu-digital-saya` |
| Settings | `https://github.com/AchariusM/kartu-digital-saya/settings` |
| Pages Settings | `https://github.com/AchariusM/kartu-digital-saya/settings/pages` |

---

## **Sharing Your Portfolio**

Now that it's live, share it everywhere:

✅ **LinkedIn** - Add to profile
✅ **Resume** - Include the link
✅ **Email** - Send to contacts
✅ **Twitter/Social** - Post the link
✅ **Job Applications** - Include in cover letter

---

## **Next Steps**

### To Make Future Changes:

1. Open project in VS Code
2. Edit files (e.g., update skills in `components/skills.html`)
3. Run in terminal:
```bash
git add .
git commit -m "Update skills section"
git push origin main
```
4. Wait 1-2 minutes
5. Refresh your live site to see changes

### To Add a Custom Domain (Optional):

1. Buy a domain (Namecheap, GoDaddy, etc.)
2. Go to Settings → Pages
3. Under "Custom domain", enter your domain
4. Follow DNS setup instructions
5. Your site is now at `your-domain.com`

---

## **Key Points to Remember**

✅ Repository must be **public**
✅ `index.html` must be in **root folder**
✅ Deployment takes **1-2 minutes** first time
✅ Updates are **automatic** after you push
✅ URL format: `https://USERNAME.github.io/REPO-NAME`

---

## **Support**

Having issues? Check:
- [GitHub Pages Official Docs](https://docs.github.com/en/pages)
- Repository Settings → Pages (for error messages)
- Browser Console (F12) for errors

---

**Congratulations! Your portfolio is now live on the internet!** 🎉
