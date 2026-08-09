# Setup Guide — Sudeep's GitHub Profile README

This turns your GitHub profile page (github.com/sudeep-patali) into the page below.
Follow these steps exactly — it takes about 5 minutes.

## 1. Create the special profile repository
GitHub shows a README on your profile only if you have a repo with the **exact same name as your username**.

1. Go to https://github.com/new
2. Repository name: `sudeep-patali` (must match your username exactly)
3. Make it **Public**
4. Check "Add a README file"
5. Click **Create repository**

## 2. Upload these files
In the new repo, upload everything from this folder, keeping the structure:

```
sudeep-patali/
├── README.md
├── assets/
│   ├── header-banner.svg
│   ├── about-card.svg
│   ├── skills-orbit.svg
│   ├── section-tech.svg
│   ├── section-projects.svg
│   ├── section-stats.svg
│   ├── line-divider.svg
│   ├── wave-footer.svg
│   ├── snake-dark.svg      (empty placeholder — auto-generated)
│   └── snake-light.svg     (empty placeholder — auto-generated)
└── .github/
    └── workflows/
        └── snake.yml
```

Easiest way: on the repo page, click **Add file → Upload files**, drag the whole folder in, and commit directly to `main`.

## 3. Enable the snake animation workflow
1. Go to the repo's **Actions** tab and enable workflows if prompted.
2. Go to **Settings → Actions → General → Workflow permissions**, select **Read and write permissions**, save.
3. Go to **Actions → 🐍 Generate Contribution Snake → Run workflow** to trigger it manually the first time.
   It will regenerate daily after that.

## 4. Fix the project links
The README links to `github.com/sudeep-patali/AIVA`, `.../NodeX`, and `.../CRC-ID`. Rename your actual
repos to match (or edit the links in README.md) so the stars/last-commit badges resolve correctly.

## 5. Double-check personal info
Everything is pulled from your resume — verify before publishing:
- Email: mesudee13579@gmail.com
- LinkedIn: linkedin.com/in/sudeep-patali-259671297
- Portfolio: sudeepportfolio11.netlify.app

That's it — visit github.com/sudeep-patali and your new profile page will be live.
