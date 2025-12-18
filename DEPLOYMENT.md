# GitHub Pages Deployment Guide

## Step-by-Step Instructions

### 1. Initialize Git Repository
```bash
cd cardinal-calculator
git init
git add .
git commit -m "Initial commit: Cardinal Calculator"
```

### 2. Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `cardinal-calculator`
3. Description: "Financial TVM Calculator with Stanford Cardinal Branding"
4. Keep it **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README (we already have one)
6. Click "Create repository"

### 3. Push to GitHub
```bash
git remote add origin https://github.com/matthewdlang18/cardinal-calculator.git
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages
1. Go to your repository: https://github.com/matthewdlang18/cardinal-calculator
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Keep folder as **/ (root)**
6. Click **Save**
7. Wait 1-2 minutes for deployment

### 5. Access Your Website
Your calculator will be live at:
**https://matthewdlang18.github.io/cardinal-calculator/**

---

## Quick Commands (All-in-One)

Run these commands from the `/Users/mattlang/Dropbox/Matt/2026/IFDM/` directory:

```bash
cd cardinal-calculator
git init
git add .
git commit -m "Initial commit: Cardinal Calculator with TVM calculations, scientific calculator, and save results feature"
git remote add origin https://github.com/matthewdlang18/cardinal-calculator.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings!

---

## Future Updates

To update your website after making changes:

```bash
cd cardinal-calculator
git add .
git commit -m "Description of your changes"
git push
```

Changes will be live in 1-2 minutes!

---

## Custom Domain (Optional)

To use a custom domain like `calculator.matthewlang.com`:

1. Add a file named `CNAME` with your domain
2. Configure DNS with your domain provider
3. Add CNAME record pointing to `matthewdlang18.github.io`

---

## Troubleshooting

**Images not showing?**
- Make sure image files are in the same directory as index.html
- Check that filenames match exactly (case-sensitive)

**404 Error?**
- Wait 2-3 minutes after enabling GitHub Pages
- Make sure the repository is public
- Verify the branch is set to "main" in Pages settings

**Need help?**
Check GitHub Pages status: https://github.com/matthewdlang18/cardinal-calculator/settings/pages
