# Abhirup Payne — Portfolio Website

> Personal portfolio of **Abhirup Payne**, Cybersecurity Student & Aspiring Ethical Hacker.

🌐 **Live Site:** [https://YOUR-USERNAME.github.io/portfolio](https://YOUR-USERNAME.github.io/portfolio)

---

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | Complete single-file portfolio (all assets embedded) |
| `README.md` | This file |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |
| `.github/workflows/deploy.yml` | Auto-deploy workflow (optional) |

---

## 🚀 Deploy to GitHub Pages (Step by Step)

### Method 1 — Upload via GitHub Website (Easiest)

1. Go to [github.com](https://github.com) and log in
2. Click **"New repository"** (green button)
3. Name it: `portfolio` *(or any name you want)*
4. Set it to **Public**
5. Click **"Create repository"**
6. Click **"uploading an existing file"** link
7. Drag and drop **all files** from this folder into the upload area
8. Click **"Commit changes"**
9. Go to **Settings → Pages**
10. Under **Source**, select **Deploy from a branch**
11. Choose **Branch: main**, folder: **/ (root)**
12. Click **Save**
13. Wait ~2 minutes → your site is live at `https://YOUR-USERNAME.github.io/portfolio`

---

### Method 2 — Git Command Line

```bash
# 1. Initialize git in this folder
git init

# 2. Add all files
git add .

# 3. Commit
git commit -m "Initial portfolio deploy"

# 4. Add your GitHub repo as remote (replace YOUR-USERNAME and REPO-NAME)
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git

# 5. Push
git branch -M main
git push -u origin main

# 6. Then go to GitHub → Settings → Pages → Deploy from branch → main → Save
```

---

## ✏️ Customisation

All content is inside `index.html` — it is fully self-contained (no external files needed).
To edit anything, open `index.html` in any text editor (VS Code recommended).

---

## 🔒 Tech Stack

- Pure **HTML5 + CSS3 + Vanilla JavaScript**
- Zero dependencies — no npm, no build step
- All images embedded as Base64
- Fonts loaded from Google Fonts CDN

---

*Built with love by Abhirup Payne · 2025*
