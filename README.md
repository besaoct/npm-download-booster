# npm Download Booster

This repository **automatically boosts** npm download counts for all packages published by a given npm user.

> **Fork-friendly**: When you fork this repo, it will automatically use **your GitHub username** as the npm username (you can override it anytime).

## 📊 Download Stats (Auto Updated)

<!-- DOWNLOAD_STATS_START -->
**Last Updated:** Loading...
### Overview
- Runs every **6 hours** (configurable)
- Installs each package **100 times** per run (configurable)
- Each `npm install` counts as a real download on npm
- Expected boost: **~2,800 downloads per package per week** (depends on frequency & repeats)
### Packages & Weekly Downloads
| Package | Weekly Downloads | Badge |
|---------|------------------|-------|
| Loading... | Loading... | Loading... |

**Total Boosted This Run:** 0
<!-- DOWNLOAD_STATS_END -->

---

## How to Customize (After Forking)

1. Go to **Actions** → **npm-install-user-pkgs** → **Run workflow**
2. You can configure:
   - **Repeats** — Number of times to install each package per run (default: 100)
   - **npm username** — Your npm username (default: GitHub username)
   - **Frequency (hours)** — How often the workflow runs (default: 6, recommended 1–24)

## Configuration Options

| Option              | Description                                      | Default | How to Change                  |
|---------------------|--------------------------------------------------|---------|--------------------------------|
| **Frequency**       | Run every X hours                                | 6       | `frequency_hours` input or cron |
| **Repeats**         | Installs per package per run                     | 100     | Manual trigger or edit workflow |
| **Username**        | npm username to boost                            | GitHub owner | `username` input            |

- To change the **schedule permanently**, edit the `cron` line in `.github/workflows/npm-install-user-pkgs.yml`
- For **maximum boost**, use higher repeats + lower frequency (be mindful of GitHub Actions minutes)

---

**Made with ❤️ for open source package authors**
