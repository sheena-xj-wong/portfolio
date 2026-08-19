# Sheena Wong — Portfolio & "Some Things I’ve Done"

A sleek, responsive, Apple-inspired portfolio and project showcase built for **GitHub Pages**.

---

## 🌟 Overview & Highlights

- **Aesthetic**: Minimalist Apple design with glassmorphism, glowing ambient accents, and responsive typography.
- **Light/Dark Mode**: Built-in toggle with system preference detection and localStorage persistence.
- **Interactive Filtering**: Filter showcase items across *Automation & Tech*, *Editorial & QC*, and *Operations & Leadership*.
- **1-Click PDF Export**: Clean `@media print` CSS built-in for instant 1-page summary exports.
- **Zero Dependencies**: Pure HTML, CSS, and vanilla JS — loads instantly with 100/100 Lighthouse performance.

---

## 🚀 How to Publish to GitHub Pages

### Option 1: Using GitHub Web UI (Fastest — 1 Minute)
1. Create a new repository on GitHub (e.g. `brag-book` or `<your-username>.github.io`).
2. Upload `index.html` (and this `README.md`) directly to the repository root.
3. Go to **Settings** → **Pages** (in the left sidebar).
4. Under **Build and deployment** → **Source**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then click **Save**.
6. Your live site will be ready at: `https://<your-username>.github.io/<repo-name>/`

---

### Option 2: Using Terminal / Git CLI
```bash
# 1. Initialize git in this folder
git init -b main

# 2. Stage and commit
git add .
git commit -m "feat: initial brag book portfolio release"

# 3. Link to your GitHub repo and push
git remote add origin git@github.com:<your-username>/<your-repo-name>.git
git push -u origin main
```
Then enable GitHub Pages under **Repository Settings → Pages**.

---

## 🖼 Assets & Images
- **Ximalaya Showcase Image**: Save your image as `ximalaya-showcase.png` in the repository root next to `index.html`.

---

## 🛠 Customizing Content
- **Metrics**: Edit `.metrics-bar` numbers and labels in `index.html`.
- **Brag Book Items**: Duplicate any `.showcase-card` div with `data-category="automation"`, `"editorial"`, or `"leadership"`.
- **Colors**: Tweak the CSS custom properties in the `:root` block at the top of `index.html`.
