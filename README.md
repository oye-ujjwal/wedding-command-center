# Wedding Command Center

A lightweight wedding task manager for Ujjwal & Khushbu. Runs in a browser and saves data in that browser's local storage.

## Features
- Create event folders/categories
- Add, edit, delete tasks
- Set assignee, deadline, status and description
- Add/edit/delete comments
- Search and filter tasks
- Mobile responsive
- No build step required

## Run locally
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a GitHub repository (e.g. `wedding-command-center`).
2. Upload `index.html` and `README.md`.
3. In repository Settings -> Pages, select Deploy from branch.
4. Choose `main` and `/ (root)`, save.
5. Open the published URL.

## Data limitation
This starter version stores data in local browser storage. It is NOT synced between devices or browsers. For cross-device sharing and access, connect Firebase (Firestore + Authentication) or another cloud database before relying on it as a shared wedding planner.
