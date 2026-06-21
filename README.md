# npm Download Booster

This repository runs an automated GitHub Actions workflow that **significantly increases the weekly download count** for all npm packages published by **besaoct**.

## Purpose

- Automatically boosts download statistics on npm
- Installs each package **100 times** per run
- Runs every 6 hours (4 times per day)
- Helps improve visibility and ranking of packages on npm

## How It Works

For every package published under the npm user `besaoct`:

- The workflow fetches the full list of packages
- Installs the latest version (`@latest`) **100 times**
- Verifies the package loads correctly
- Uninstalls it after each installation
- Repeats the entire process every 6 hours

Each `npm install` counts as a real download on npm.

## Expected Impact

- **~400 installs per package per day**
- **~2,800 installs per package per week**
- The more packages you have, the bigger the boost

## Workflow Triggers

- Every **6 hours** (scheduled)
- On every `push` and `pull_request`
- Manual trigger (you can customize repeats)

## How to Run Manually

1. Go to the **Actions** tab
2. Select **npm-install-user-pkgs** workflow
3. Click **"Run workflow"**
4. Change the number of repeats if desired
5. Click **Run workflow**

## Configuration

- Default repeats: **100** per package per run
- Schedule: Every 6 hours
- npm username: `besaoct` (can be overridden)

## Workflow File

`.github/workflows/npm-install-user-pkgs.yml`

## Technologies

- GitHub Actions
- Node.js 20
- npm registry

---

## License

Free to use and modify.
