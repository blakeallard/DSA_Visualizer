# DSA — Blake Allard’s Algorithm Visualizer

Interactive visualizations for Data Structures & Algorithms problems I’ve studied and solved.

Live Site:
https://blakeallard.github.io/DSA_Visualizer/

---

## Overview

This project turns LeetCode-style problems into interactive visual demonstrations.

Instead of only writing C++ solutions, each problem is rebuilt visually to reinforce:

- Traversal patterns
- Pointer movement
- State transitions
- Algorithm flow
- Time and space intuition

Built with plain HTML, CSS, and JavaScript.
Deployed using GitHub Pages.

---

## Tech Stack

- HTML
- CSS
- JavaScript (Vanilla)
- GitHub Pages

No frameworks. No build tools. No dependencies.

---

## Project Structure

DSA_Visualizer/
├── index.html
├── README.md
└── problems/
    ├── spiral-matrix/
    │   └── index.html
    ├── search-2d-matrix/
    │   └── index.html
    ├── heap-insert/
    │   └── index.html

Each problem lives in its own folder with a fully self-contained visualizer.

---

## Deployment

This site is automatically deployed using GitHub Pages from the `main` branch.

To update the site:

git add .
git commit -m "Update visualizer"
git push

Changes go live automatically.

---

## Current Problems

- Spiral Matrix — Matrix Traversal
- Search 2D Matrix — Binary Search
- Heap Insert — Heap / Tree

More problems will be added as I progress through advanced algorithm patterns.

---

## Run Locally

Open `index.html` directly in your browser.

Or run a simple local server:

npx serve .
