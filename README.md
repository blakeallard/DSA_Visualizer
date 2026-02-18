# 🌀 DSA.viz — Blake's Algorithm Visualizer

Interactive visualizations for every LeetCode problem I've gotten stuck on.
Built with vanilla HTML/CSS/JS. No frameworks, no build step, deploys instantly to GitHub Pages.

---

## 🚀 Deploy to GitHub Pages (one-time setup)

### 1. Create a GitHub repo

Go to [github.com/new](https://github.com/new) and create a new repo called `dsa-viz` (or anything you like).
Make it **public** (required for free GitHub Pages).

### 2. Push this folder

```bash
cd dsa-visualizer
git init
git add .
git commit -m "Initial commit — Spiral Matrix"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/dsa-viz.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source" select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**

Your site will be live at:
```
https://YOUR_USERNAME.github.io/dsa-viz/
```
(takes ~60 seconds to deploy)

---

## ➕ Adding a New Problem

When you bring me a new LeetCode problem, I'll:

1. Create `problems/PROBLEM-NAME/index.html` with a full visualizer
2. Add a new card to `index.html`

Then you just run:

```bash
git add .
git commit -m "Add: Problem Name visualizer"
git push
```

GitHub Pages auto-deploys — your site updates in ~30 seconds.

---

## 🗂 Project Structure

```
dsa-visualizer/
├── index.html                        ← Home page (problem grid)
├── README.md
└── problems/
    ├── spiral-matrix/
    │   └── index.html                ← Spiral Matrix visualizer
    ├── two-sum/
    │   └── index.html                ← (coming soon)
    └── ...
```

---

## 🖥 Run Locally

Just open `index.html` in your browser — no server needed.

Or with a local server for hot reload:
```bash
npx serve .
# → http://localhost:3000
```

---

## Problems

| # | Problem | Difficulty | Status |
|---|---------|------------|--------|
| 054 | Spiral Matrix | Medium | ✅ Live |
| 001 | Two Sum | Easy | 🔜 Soon |
| 011 | Container With Most Water | Medium | 🔜 Soon |
| 042 | Trapping Rain Water | Hard | 🔜 Soon |
| 102 | Binary Tree Level Order Traversal | Medium | 🔜 Soon |
| 200 | Number of Islands | Medium | 🔜 Soon |
| 322 | Coin Change | Medium | 🔜 Soon |
