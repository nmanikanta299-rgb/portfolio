# Manikanta — Performance Marketing Portfolio

A single-page, animated portfolio website for a Performance Marketing Manager, built with plain HTML/CSS/JS (no build step required).

## 🌐 Live Preview
Once deployed with GitHub Pages, your site will be available at:
`https://<your-username>.github.io/<repo-name>/`

## ✨ Features
- Animated particle background & typing effect hero section
- Scroll-reveal animations and animated counters
- Sections: Home, About, Experience Timeline (9 roles), Skills, Projects, Achievements, Why Hire Me, Case Studies, Contact
- Fully responsive (mobile hamburger nav included)
- Contact form + "Download Resume" button that opens the visitor's email client via `mailto:`

## 📁 Project Structure
```
.
├── index.html      # entire site (HTML + CSS + JS in one file)
├── README.md       # this file
└── .gitignore
```

## 🚀 How to Upload to GitHub

### Option A — Using GitHub's website (no terminal needed)
1. Go to [github.com](https://github.com) and log in.
2. Click the **+** icon (top right) → **New repository**.
3. Name it, e.g. `portfolio`, keep it **Public**, then click **Create repository**.
4. On the new repo page, click **uploading an existing file**.
5. Drag and drop `index.html`, `README.md`, and `.gitignore` into the upload box.
6. Scroll down and click **Commit changes**.

### Option B — Using Git on your computer
```bash
# 1. Create a folder and add these files to it
cd manikanta-portfolio

# 2. Initialize git
git init
git add .
git commit -m "Initial commit: portfolio site"

# 3. Create a new repo on GitHub (via the website) first, then:
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## 🌍 Enable GitHub Pages (to get a free live link)
1. In your GitHub repo, go to **Settings** → **Pages**.
2. Under **Branch**, select `main` and folder `/ (root)`.
3. Click **Save**.
4. Wait a minute, then your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## 🛠️ Local Preview
Just double-click `index.html`, or run a quick local server:
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

## ✏️ Customization
- Update contact details directly inside `index.html`.
- The resume button currently opens an email draft requesting the resume — replace the `mailto:` link with a direct file/Drive link if you'd rather offer a one-click download.
- Colors and fonts are controlled via CSS variables at the top of the `<style>` block (`:root { ... }`).
