# Geocube Ltd Corporate Website

Minimal corporate website for Geocube Ltd.

## Deployment

This site is deployed using Cloudflare Pages.

### Setup Instructions

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Click "Create a project"
3. Connect to GitHub and select the `geocube.work` repository
4. Configure build settings:
   - **Framework preset**: None
   - **Build command**: (leave empty)
   - **Build output directory**: `/`
5. Click "Save and Deploy"

### Custom Domain Setup

1. In Cloudflare Pages project settings, go to "Custom domains"
2. Add `geocube.work` as a custom domain
3. Cloudflare will provide DNS records to configure
4. Update your domain's DNS settings with the provided records

### Automatic Deployments

Once connected, Cloudflare Pages will automatically deploy:
- Every push to the `main` branch
- Any changes made to the repository

No build step needed - this is a static HTML/CSS site.
