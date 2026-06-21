# npm Download Booster

This repository **automatically boosts** npm download counts for all packages published by a given npm user.

> **Fork-friendly**: When you fork this repo, it will automatically use **your GitHub username** as the npm username. You can change it anytime.

## 📊 Download Stats (Auto Updated Every 6 Hours)

<!-- DOWNLOAD_STATS_START -->
**Last Updated:** Loading...

### Overview

- Runs every **6 hours**
- Installs each package **100 times** per run
- Each `npm install` counts as a real download on npm
- Expected boost: **~2,800 downloads per package per week**

### Packages & Weekly Downloads

| Package | Weekly Downloads | Badge |
|---------|------------------|-------|
| Loading... | Loading... | Loading... |

**Total Boosted This Run:** 0
<!-- DOWNLOAD_STATS_END -->

---

## How to Customize (After Forking)

1. Go to **Actions** → **npm-install-user-pkgs** → **Run workflow**
2. You can change:
   - **Repeats** (number of installs per package)
   - **npm username** (your npm username)

## Configuration Options

- **Schedule**: Change the cron expression in the workflow file
- **Repeats**: Default = 100 (change via manual run or edit workflow)
- **Username**: Auto-detects from GitHub username on fork

---

**Made with ❤️ for package authors**
