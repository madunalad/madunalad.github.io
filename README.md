# Dheeraj Kumar — Portfolio

Personal portfolio website built with pure HTML, CSS, and JavaScript. No frameworks, no build tools — just drop it on GitHub Pages and it works.

## 🚀 Deploy on GitHub Pages (3 Steps)

### Step 1 — Create a new repo
Go to [github.com/new](https://github.com/new) and create a repository named exactly:
```
YOUR_GITHUB_USERNAME.github.io
```
Example: if your username is `dheeraj-kumar`, name it `dheeraj-kumar.github.io`

### Step 2 — Upload the file
- Click **Add file → Upload files**
- Upload `index.html`
- Click **Commit changes**

### Step 3 — Enable GitHub Pages
- Go to **Settings → Pages**
- Under **Source**, select **Deploy from a branch**
- Branch: `main`, Folder: `/ (root)`
- Click **Save**

✅ Your site will be live at `https://YOUR_GITHUB_USERNAME.github.io` within ~60 seconds.

---

## ✏️ How to Customize

Open `index.html` in any text editor (VS Code recommended) and find these sections:

### Update your name / title
```html
<!-- Line ~220 -->
<h1 class="hero-name">
  Dheeraj<br><em>Kumar.</em>
</h1>
```

### Update contact info
```html
<!-- Search for: madunalad@gmail.com -->
<!-- Search for: +1 312-973-8814 -->
<!-- Search for: linkedin.com/in/dheeraj -->
```

### Update stats (hero section)
```html
<div class="stat-val" data-count="10">0</div>  <!-- changes to 10 with animation -->
<div class="stat-lbl">M+ Records/Day Processed</div>
```

### Add/edit skills
Find the `#skills` section and add `<span class="skill-tag">New Skill</span>` inside any category. Use `class="skill-tag featured"` to highlight it in gold.

### Add/edit projects
Copy an existing `.impact-card` block inside `#impact` and update the content.

---

## 🎨 Color Customization

At the top of the `<style>` block, change these CSS variables:

```css
:root {
  --bg:    #0a0a08;   /* Main background */
  --gold:  #c8a96e;   /* Accent color — change this to any color you like */
  --text:  #e8e6df;   /* Primary text */
  --muted: #6e6c65;   /* Secondary text */
}
```

To switch to a **light theme**, swap:
- `--bg: #fafaf8`
- `--text: #1a1a18`
- `--surface: #f0eeea`
- `--card: #e8e6e0`

---

## 📁 File Structure

```
YOUR_REPO/
└── index.html    ← The entire portfolio (self-contained)
└── README.md     ← This file (optional)
```

Everything is in a single file — fonts load from Google Fonts (CDN), no local assets needed.

---

## ✨ Features

- **Fully responsive** — works on mobile, tablet, desktop
- **Smooth scroll reveal** animations on every section
- **Count-up stats** that animate when scrolled into view
- **Custom cursor** with magnetic hover effect (desktop only)
- **Mobile hamburger menu**
- **Noise texture overlay** for depth
- **Zero dependencies** — no npm, no build step, no framework

---

## 📬 Contact

Dheeraj Kumar — [madunalad@gmail.com](mailto:madunalad@gmail.com)
