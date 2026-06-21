# npm Download Booster

This repository **automatically boosts** npm download counts for all packages published by a given npm user.

> **Fork-friendly**: When you fork this repo, it will automatically use **your GitHub username** as the npm username (you can override it anytime via workflow dispatch).

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

## How to Customize (After Forking)

1. Go to **Actions** → **npm-install-user-pkgs** → **Run workflow**
2. You can set:
   - **Repeats** → Number of installs per package per run
   - **npm username** → Your npm username
   - **Frequency (hours)** → How often it runs (1–24)

## Configuration Options

| Option              | Description                            | Default | How to Change                     |
|---------------------|----------------------------------------|---------|-----------------------------------|
| Frequency           | Run every X hours                      | 6       | `frequency_hours` input or cron   |
| Repeats             | Installs per package                   | 100     | Manual trigger                    |
| Username            | npm username to boost                  | GitHub owner | `username` input               |

---

**Made with ❤️ for open source package authors**
