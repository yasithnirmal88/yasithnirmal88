# Setup Instructions for Your GitHub Profile README

Congratulations! You've just set up a premium GitHub profile README. Follow these steps to make it live:

## Step 1: Create/Verify the Special Repository

Your README is already in place at `D:\GitHub\yasithnirmal88\README.md`. For it to appear on your GitHub profile, you need to create a repository with the exact name as your username.

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `yasithnirmal88` (must match your username exactly)
3. Set to **Public**
4. Initialize with: No README, .gitignore, or license (we already have files)
5. Click **Create repository**

## Step 2: Push Your Files to GitHub

Open a terminal in your project directory and run:

```bash
cd D:\GitHub\yasithnirmal88

git init
git add .
git commit -m "feat: add premium GitHub profile README"
git branch -M main
git remote add origin https://github.com/yasithnirmal88/yasithnirmal88.git
git push -u origin main
```

## Step 3: Enable GitHub Actions for Snake Animation

The snake animation requires GitHub Actions to generate it:

1. Go to your repository: [github.com/yasithnirmal88/yasithnirmal88](https://github.com/yasithnirmal88/yasithnirmal88)
2. Navigate to **Actions** tab
3. If prompted, enable GitHub Actions
4. The workflow will run automatically on schedule (daily) or you can manually trigger it
5. After it runs successfully, it will create an `output` branch with the snake SVGs

> **Note:** The snake animation may take a few minutes to generate on first run.

## Step 4: Update Your Email (Optional)

In the README, there's a placeholder email. If you'd like to update it:
1. Open `README.md`
2. Find `mailto:yasithnirmal88@gmail.com` and replace with your actual email
3. Commit and push the changes

## Tips for Customization

- **Colors**: The theme uses `#00d9ff` (cyan) as accent color on a dark `#0d1117` background. You can change these in the badge URLs and SVG.
- **Featured Projects**: Edit the project cards in the "Featured Projects" section to showcase your best work.
- **Tech Stack**: Add or remove badges based on your preferences.
- **Banner**: You can customize `assets/banner.svg` using any SVG editor or replace it with your own image.

## Alternative Color Themes

If you'd like to try different accents:

| Theme | Accent Color | Style |
|-------|--------------|-------|
| Cyberpunk Purple | `#a855f7` | Futuristic, hacker aesthetic |
| Matrix Green | `#00ff41` | Classic terminal look |
| Sunset Orange | `#ff6b35` | Warm, energetic |
| Neon Pink | `#ff10f0` | Bold, creative |

To use a different theme, replace `00d9ff` with your chosen color throughout the README and banner.

## Maintenance

- The snake animation updates daily automatically
- GitHub stats cards update in real-time
- Keep your pinned repositories updated on your profile for best visibility

---

**Your profile will be live at:** [github.com/yasithnirmal88](https://github.com/yasithnirmal88)
