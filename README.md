# npm Download Booster

This repository automatically boosts npm download counts for all packages published by a given npm user.

**Fork-friendly:** When you fork this repo, it will automatically use your GitHub username as the npm username (you can override it anytime via workflow dispatch).

## How to Use

1. Fork this repository
2. Go to **Actions → npm-install-user-pkgs → Run workflow**
3. Configure the inputs:
   - **Repeats** — Number of installs per package (default: 1)
   - **Username** — Your npm username (default: GitHub username)
   - **Frequency (hours)** — How often it runs (default: 24)

## Configuration Options

| Option | Description | Default | How to Change |
| --- | --- | --- | --- |
| Frequency | Run every X hours | 24 | Workflow dispatch or edit cron |
| Repeats | Installs per package per run | 1 | Manual trigger |
| Username | npm username to boost | GitHub owner | Manual trigger |

⚠️ **Important Notes**

- This tool uses real `npm install` commands — each install counts as a legitimate download on npm.
- GitHub Actions has free minute limits (especially on public repositories).
- npm may apply rate limiting if you use very high repeats or very low frequency.
- Use responsibly and respect npm's Terms of Service.

## 📊 Download Stats

**Last Updated:** 2026-07-15 02:06 UTC

### Overview
- Runs every **24 hours** (configurable)
- Installs each package **1 times** per run (configurable)

### Cumulative Stats
- **Total Runs:** 22
- **Total Boosted:** 154 downloads
- **Boosted This Run:** 7 downloads
- **Average per Run:** 7 downloads
- **Total Packages:** 7
- **Estimated Weekly Boost:** ~49 downloads
- **Last Run:** 2026-07-15 02:06 UTC

### Proxy Usage (This Run)
- **Strategy:** Proxy first → Direct fallback
- **Proxy Attempts:** 17
- **Proxy Successes:** 2
- **Proxy Success Rate:** 11%
- **Sources:** ProxyScrape, TheSpeedX, Proxifly, Monosans

### Packages & Stats
| Package | Badge | Total Boosted | Est. Weekly |
|---------|-------|---------------|-------------|
| [gramobase](https://www.npmjs.com/package/gramobase) | <img alt="Downloads" src="https://img.shields.io/npm/dw/gramobase"> | 22 | ~7 |
| [drivespread](https://www.npmjs.com/package/drivespread) | <img alt="Downloads" src="https://img.shields.io/npm/dw/drivespread"> | 22 | ~7 |
| [create-espkg](https://www.npmjs.com/package/create-espkg) | <img alt="Downloads" src="https://img.shields.io/npm/dw/create-espkg"> | 22 | ~7 |
| [justy](https://www.npmjs.com/package/justy) | <img alt="Downloads" src="https://img.shields.io/npm/dw/justy"> | 22 | ~7 |
| [genfunc](https://www.npmjs.com/package/genfunc) | <img alt="Downloads" src="https://img.shields.io/npm/dw/genfunc"> | 22 | ~7 |
| [next-react-share](https://www.npmjs.com/package/next-react-share) | <img alt="Downloads" src="https://img.shields.io/npm/dw/next-react-share"> | 22 | ~7 |
| [nuniq](https://www.npmjs.com/package/nuniq) | <img alt="Downloads" src="https://img.shields.io/npm/dw/nuniq"> | 22 | ~7 |

*Package names are linked to their npm page. Total Boosted = lifetime successful installs.*
