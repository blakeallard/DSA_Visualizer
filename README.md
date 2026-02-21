</div>

---

## Preview

<div align="center">

![DSA Visualizer Demo](assets/demo.gif)

</div>

---

<div align="center">

<br />

```
██████╗ ███████╗ █████╗     ██╗   ██╗██╗███████╗
██╔══██╗██╔════╝██╔══██╗    ██║   ██║██║╚══███╔╝
██║  ██║███████╗███████║    ██║   ██║██║  ███╔╝ 
██║  ██║╚════██║██╔══██║    ╚██╗ ██╔╝██║ ███╔╝  
██████╔╝███████║██║  ██║     ╚████╔╝ ██║███████╗
╚═════╝ ╚══════╝╚═╝  ╚═╝      ╚═══╝  ╚═╝╚══════╝
```

**Interactive algorithm visualizations built to expose the mechanics behind the code.**

[![Live Demo](https://img.shields.io/badge/LIVE%20DEMO-%E2%86%92-FF4444?style=for-the-badge&labelColor=0d0d0d)](https://blakeallard.github.io/DSA_Visualizer/)
[![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://blakeallard.github.io/DSA_Visualizer/)
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://blakeallard.github.io/DSA_Visualizer/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://blakeallard.github.io/DSA_Visualizer/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://blakeallard.github.io/DSA_Visualizer/)

<br />

## Why This Exists

Writing a solution is one thing. *Understanding* it is another.

Most algorithm practice stops at correctness — you get the right answer, move on. This project takes a different approach: every algorithm is reconstructed as a live visual simulation so you can **watch** it think.

> The goal isn't just to pass the interview. It's to build algorithmic intuition that sticks.

---

## Visualizations

| Problem | Category | What You'll See |
|---|---|---|
| **Spiral Matrix** | Matrix Traversal | Boundary contraction, direction switching, layer peeling |
| **Search 2D Matrix** | Binary Search | Coordinate mapping, mid-point targeting, elimination zones |
| **Heap Insert** | Heap / Trees | Node placement, parent comparisons, sift-up restructuring |

> More problems added continuously as I progress through advanced algorithm patterns.

---

## What Each Visualization Exposes

Rather than just showing a final answer, each simulation reveals:

```
Pointer movement       →  watch indices shift in real time
State transitions      →  see exactly when conditions flip
Traversal mechanics    →  follow the path step by step
Heap restructuring     →  observe sift-up/sift-down live
Matrix boundary logic  →  see the shrinking search space
Binary search flow     →  track the elimination of possibilities
```

---

## Tech Stack

```
No frameworks. No build tools. No dependencies.
```

| Layer | Choice | Why |
|---|---|---|
| Structure | HTML | Semantic, zero overhead |
| Style | CSS | Custom animations, zero bloat |
| Logic | Vanilla JavaScript | Full control, no abstraction layer |
| Deploy | GitHub Pages | Instant, automatic, free |

Every problem is **fully self-contained** in its own directory. Open any `index.html` directly in a browser — it just works.

---

## Project Structure

```
DSA_Visualizer/
├── index.html                  ← Main landing page
├── README.md
├── assets/
│   └── demo.gif
└── problems/
    ├── spiral-matrix/
    │   └── index.html
    ├── search-2d-matrix/
    │   └── index.html
    └── heap-insert/
        └── index.html
```

---

## Run Locally

**Option 1 — Just open it:**
```bash
open index.html
```

**Option 2 — Serve it:**
```bash
npx serve .
```

---

## Deploy

Pushes to `main` deploy automatically via GitHub Pages.

```bash
git add .
git commit -m "your message"
git push
```

Done. Changes are live within seconds.

---

<div align="center">

**Built by [Blake Allard](https://github.com/blakeallard)**
<br />
CS student @ Saddleback College → UCI Transfer 2027

<br />

*If this helped you think about algorithms differently, give it a ⭐*

</div>
