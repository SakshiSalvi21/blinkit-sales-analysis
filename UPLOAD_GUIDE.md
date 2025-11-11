# Quick Upload Guide

1) Create a new empty repo on GitHub (without README).
2) On your computer:
   ```bash
   git init
   git remote add origin <YOUR_GITHUB_REPO_URL>
   git add .
   git commit -m "Initial commit: Blinkit Power BI dashboard"
   git branch -M main
   git push -u origin main
   ```
3) After recording screenshots, add them into `docs/screenshots/` and push again:
   ```bash
   git add docs/screenshots/*
   git commit -m "Add screenshots"
   git push
   ```