# Keyan Dehghan: Personal Website

This is a minimal scaffold for a static personal website.

## Files

- `index.html` — Main HTML file for your website.
- `style.css` — CSS file for styling your pages.
- `scripts.js` — Optional JavaScript file for interactivity.
- `images/` — Folder for images.

# Publishing Your Site on GitHub Pages

Follow these steps to publish your minimal personal website on GitHub Pages.

---

## 1. Initialize Local Git Repository

```bash
cd personal-website
git init
git add .
git commit -m "Initial site scaffold"
git branch -M main
```


## 2. Create a Repository on GitHub

**Option 1: Using the Web**

1. Go to [https://github.com/new](https://github.com/new) and create a new repository.
2. Give your repository a name (for example, Keyan-Dehghan) and optionally a description.
3. Keep the repository **public**.
4. After creating the repository, GitHub will show instructions to push an existing repository. Follow them:
bash
git remote add origin https://github.com/Keyan-Dehghan/Keyan-Dehghan.git
git branch -M main
git push -u origin main


## 3. Enable GitHub Pages

**Using the Web:**
1. Go to your repository → Settings → Pages.
2. Under **Source**, select:
   - Branch: main
   - Folder: / (root)
3. Click **Save**.
4. Your site will be published at: https://Keyan-Dehghan.github.io/Keyan-Dehghan/


--- **Using GitHub CLI:**

- You can enable GitHub Pages using GitHub CLI commands (gh) or adjust the settings via the repository settings UI.

---

**Optional: Custom Domain**
1. Add a CNAME file to your repository containing your custom domain name.
2. Configure your domain's DNS to point to GitHub Pages.
