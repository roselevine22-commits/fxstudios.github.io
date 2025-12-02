# fxstudios.github.io

## Deployment Instructions

This repository is configured for GitHub Pages deployment using GitHub Actions.

### Configuration

- **Source Branch**: `main`
- **Source Folder**: Root (`/`)
- **Deployment Method**: GitHub Actions workflow

### How to Deploy

1. Push your changes to the `main` branch
2. The GitHub Actions workflow will automatically build and deploy your site
3. Your site will be available at: `https://roselevine22-commits.github.io/fxstudios.github.io/`

### Manual Deployment

You can also trigger a manual deployment:

1. Go to the **Actions** tab in this repository
2. Select the **Deploy to GitHub Pages** workflow
3. Click **Run workflow**
4. Select the `main` branch and click **Run workflow**

### GitHub Pages Settings

To enable GitHub Pages for this repository:

1. Go to **Settings** > **Pages**
2. Under **Build and deployment**, select **GitHub Actions** as the source
3. The workflow will handle the rest automatically