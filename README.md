# npm Download Booster

This repository **automatically boosts** npm download counts for all packages published by a given npm user.

> **Fork-friendly**: When you fork this repo, it will automatically use **your GitHub username** as the npm username (you can override it anytime).

## 📊 Download Stats (Auto Updated)

<!-- DOWNLOAD_STATS_START -->
**Last Updated:** Loading...

### Overview
- Runs every **6 hours** (configurable)
- Installs each package **100 times** per run (configurable)

### Cumulative Stats
- **Total Runs:** ...
- **Total Boosted:** ... downloads
- **Boosted This Run:** ...
- **Average per Run:** ... downloads
- **Total Packages:** ...
- **Estimated Weekly Boost:** ~... downloads
- **Last Run:** ...

### Packages & Weekly Downloads
| Package | Weekly Downloads | Badge |
|---------|------------------|-------|
| Loading... | Loading... | Loading... |
<!-- DOWNLOAD_STATS_END -->

---

## How to Use

1. **Fork** this repository
2. Go to **Actions** → **npm-install-user-pkgs** → **Run workflow**
3. Configure:
   - **Repeats**: Number of installs per package (default: 100)
   - **Username**: Your npm username (default: GitHub username)
   - **Frequency (hours)**: How often it runs (default: 6)

## Configuration Options

| Option            | Description                            | Default | How to Change                  |
|-------------------|----------------------------------------|---------|--------------------------------|
| Frequency         | Run every X hours                      | 6       | Workflow dispatch or cron      |
| Repeats           | Installs per package per run           | 100     | Manual trigger                 |
| Username          | npm username to boost                  | GitHub owner | Manual trigger             |

---

**Made with ❤️ for open source package authors**
