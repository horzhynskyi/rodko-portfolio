# Rodko Portfolio

Portfolio website for Rodko Horzhynskyi - Principal Product Designer and Design Director

## GitHub Pages Deployment

This repository is configured to automatically deploy to GitHub Pages using GitHub Actions.

### Setup Instructions

To enable GitHub Pages deployment for this repository, follow these steps:

1. Go to your repository settings: `https://github.com/horzhynskyi/rodko-portfolio/settings/pages`

2. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"

3. Once configured, the site will automatically deploy when you push to the `main` or `master` branch

4. You can also manually trigger a deployment by going to the "Actions" tab and running the "Deploy to GitHub Pages" workflow

### Accessing Your Site

After deployment, your portfolio will be available at:
- `https://horzhynskyi.github.io/rodko-portfolio/`

### Manual Deployment

You can manually trigger a deployment at any time:
1. Go to the "Actions" tab in your repository
2. Select "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

## Files

- `index.html` - Main portfolio page
- `stylesheet_*.css` - Stylesheets for the site
- `manifest.json` - Web app manifest
- `fonts/` - Custom fonts directory
- `.github/workflows/deploy.yml` - GitHub Actions deployment workflow
