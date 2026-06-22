# npm Download Booster

This repository automatically boosts npm download counts for all packages published by a given npm user.

**Fork-friendly:** When you fork this repo, it will automatically use your GitHub username as the npm username (you can override it anytime via workflow dispatch).

## How to Use

1. Fork this repository
2. Go to **Actions → npm-install-user-pkgs → Run workflow**
3. Configure the inputs:
   - **Repeats** — Number of installs per package (default: 1)
   - **Username** — Your npm username (default: GitHub username)
   - **Frequency (hours)** — How often it runs (default: 6)

## Configuration Options

| Option | Description | Default | How to Change |
| --- | --- | --- | --- |
| Frequency | Run every X hours | 6 | Workflow dispatch or edit cron |
| Repeats | Installs per package per run | 1 | Manual trigger |
| Username | npm username to boost | GitHub owner | Manual trigger |

⚠️ **Important Notes**

- This tool uses real `npm install` commands — each install counts as a legitimate download on npm.
- GitHub Actions has free minute limits (especially on public repositories).
- npm may apply rate limiting if you use very high repeats or very low frequency.
- Use responsibly and respect npm's Terms of Service.

## 📊 Download Stats

**Last Updated:** 2026-06-22 15:32 UTC

### Overview
- Runs every **6 hours** (configurable)
- Installs each package **1 times** per run (configurable)

### Cumulative Stats
- **Total Runs:** 1
- **Total Boosted:** 7 downloads
- **Boosted This Run:** 7 downloads
- **Average per Run:** 7 downloads
- **Total Packages:** 7
- **Estimated Weekly Boost:** ~196 downloads
- **Last Run:** 2026-06-22 15:32 UTC

### Proxy Usage (This Run)
- **Strategy:** Proxy first → Direct fallback
- **Proxy Attempts:** 20
- **Proxy Successes:** 1
- **Proxy Success Rate:** 5%
- **Sources:** ProxyScrape, TheSpeedX, Proxifly, Monosans

### Packages & Stats
| Package | Badge | Total Boosted | Est. Weekly |
|---------|-------|---------------|-------------|
| [gramobase](https://www.npmjs.com/package/gramobase) | <img alt="Downloads" src="https://img.shields.io/npm/dw/gramobase"> | 1 | ~28 |
| [drivespread](https://www.npmjs.com/package/drivespread) | <img alt="Downloads" src="https://img.shields.io/npm/dw/drivespread"> | 1 | ~28 |
| [create-espkg](https://www.npmjs.com/package/create-espkg) | <img alt="Downloads" src="https://img.shields.io/npm/dw/create-espkg"> | 1 | ~28 |
| [justy](https://www.npmjs.com/package/justy) | <img alt="Downloads" src="https://img.shields.io/npm/dw/justy"> | 1 | ~28 |
| [next-react-share](https://www.npmjs.com/package/next-react-share) | <img alt="Downloads" src="https://img.shields.io/npm/dw/next-react-share"> | 1 | ~28 |
| [genfunc](https://www.npmjs.com/package/genfunc) | <img alt="Downloads" src="https://img.shields.io/npm/dw/genfunc"> | 1 | ~28 |
| [nuniq](https://www.npmjs.com/package/nuniq) | <img alt="Downloads" src="https://img.shields.io/npm/dw/nuniq"> | 1 | ~28 |

*Package names are linked to their npm page. Total Boosted = lifetime successful installs.*
