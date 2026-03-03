# GitHub Deployment Instructions

## Step-by-Step Guide to Push Your Portfolio to GitHub

### Step 1: Create a GitHub Repository
1. Go to https://github.com/new
2. Repository name: **portfolio**
3. Description: "Professional data analyst portfolio with dark theme"
4. Choose **Public** (so it's visible to employers/clients)
5. Do NOT initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

### Step 2: Add Remote Repository & Push Code
After creating the repository, GitHub will show you commands. Copy and paste these commands:

```bash
git branch -M main
git remote add origin https://github.com/amar9100/portfolio.git
git push -u origin main
```

**Or if you have GitHub CLI installed, just run:**
```bash
gh repo create portfolio --public --source=. --remote=origin --push
```

### Step 3: Enable GitHub Pages
1. Go to your repository: https://github.com/amar9100/portfolio
2. Click **Settings** (top right)
3. Scroll down to **Pages** section (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. GitHub will show: "Your site is published at https://amar9100.github.io/portfolio/"

### Step 4: Customize Domain (Optional)
If you have a custom domain (e.g., amarendarreddy.com):
1. In **Pages** settings, add your custom domain
2. Update your domain's DNS settings to point to GitHub Pages
3. Follow GitHub's instructions for CNAME file

---

## Your Portfolio Domain

After enabling GitHub Pages (Step 3), your portfolio will be live at:

### 🌐 **https://amar9100.github.io/portfolio/**

This is your professional data analyst portfolio domain!

---

## What's Included in Your GitHub Repository

```
portfolio/
├── index.html       (430+ lines - Main portfolio page)
├── styles.css       (1348+ lines - Professional dark theme)  
├── script.js        (133 lines - Interactive features)
└── README.md        (Comprehensive project documentation)
```

## Next Steps After Deployment

1. ✅ Portfolio is live and accessible
2. 📤 Share your GitHub repository link with employers/clients
3. 📋 Add a link to your portfolio on your resume/LinkedIn
4. 🔗 Update GitHub profile with portfolio link

---

## Important Notes

- GitHub Pages takes 1-2 minutes to deploy after push
- Your portfolio is **automatically updated** when you push to GitHub
- All code is **version controlled** with git
- Your **repository is public** so employers can see your work

## Support

If you need help with GitHub Pages or have questions, visit:
- GitHub Pages Docs: https://pages.github.com/
- GitHub Help: https://docs.github.com/
