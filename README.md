# npm Download Booster

This repository **automatically boosts** npm download counts for all packages published by a given npm user.

> **Fork-friendly**: When you fork this repo, it will automatically use **your GitHub username** as the npm username (you can override it anytime via workflow dispatch).

## How to Use

1. **Fork** this repository
2. Go to **Actions** → **npm-install-user-pkgs** → **Run workflow**
3. Configure the inputs:
   - **Repeats** — Number of installs per package (default: 1)
   - **Username** — Your npm username (default: GitHub username)
   - **Frequency (hours)** — How often it runs (default: 6)

## Configuration Options

| Option       | Description                            | Default | How to Change                  |
|--------------|----------------------------------------|---------|--------------------------------|
| Frequency    | Run every X hours                      | 6       | Workflow dispatch or cron      |
| Repeats      | Installs per package per run           | 1       | Manual trigger                 |
| Username     | npm username to boost                  | GitHub owner | Manual trigger             |

## ⚠️ Important Notes

- This tool uses real `npm install` commands — each install counts as a legitimate download on npm.
- GitHub Actions has **free minute limits** (especially on public repositories).
- npm may apply rate limiting if you use very high repeats or very low frequency.
- Use responsibly and respect npm's [Terms of Service](https://www.npmjs.com/policies/terms).

## 📊 Download Stats (Auto Updated)

<!-- DOWNLOAD_STATS_START -->
**Last Updated:** 2026-06-22 00:16 UTC

### Overview
- Runs every **6 hours** (configurable)
- Installs each package **5 times** per run (configurable)

### Cumulative Stats
- **Total Runs:** 6
- **Total Boosted:** 875 downloads
- **Boosted This Run:** 35 downloads
- **Average per Run:** 145 downloads
- **Total Packages:** 7
- **Estimated Weekly Boost:** ~980 downloads
- **Last Run:** 2026-06-22 00:16 UTC

### Proxy Usage (This Run)
- **Strategy:** Direct connection (free proxies disabled)
- **Method:** Aggressive cache cleaning + 3 retries + --strict-ssl=false
- **Note:** More reliable than free proxies

### Packages & Weekly Downloads
| Package | Weekly Downloads | Badge |
|---------|------------------|-------|
| [gramobase](https://www.npmjs.com/package/gramobase) | 94 | [![Downloads](https://img.shields.io/npm/dw/gramobase)](https://www.npmjs.com/package/gramobase) |
| [drivespread](https://www.npmjs.com/package/drivespread) | 37 | [![Downloads](https://img.shields.io/npm/dw/drivespread)](https://www.npmjs.com/package/drivespread) |
| [create-espkg](https://www.npmjs.com/package/create-espkg) | 1 | [![Downloads](https://img.shields.io/npm/dw/create-espkg)](https://www.npmjs.com/package/create-espkg) |
| [justy](https://www.npmjs.com/package/justy) | 2 | [![Downloads](https://img.shields.io/npm/dw/justy)](https://www.npmjs.com/package/justy) |
| [next-react-share](https://www.npmjs.com/package/next-react-share) | 5 | [![Downloads](https://img.shields.io/npm/dw/next-react-share)](https://www.npmjs.com/package/next-react-share) |
| [genfunc](https://www.npmjs.com/package/genfunc) | 4 | [![Downloads](https://img.shields.io/npm/dw/genfunc)](https://www.npmjs.com/package/genfunc) |
| [nuniq](https://www.npmjs.com/package/nuniq) | 2 | [![Downloads](https://img.shields.io/npm/dw/nuniq)](https://www.npmjs.com/package/nuniq) |
<!-- DOWNLOAD_STATS_END -->
