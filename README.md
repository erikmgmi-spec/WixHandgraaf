# Handgraaf Estate Management

Standalone estate-management landing page for Handgraaf Estates.

## Deployment

The site is a static HTML deployment hosted on Netlify. Netlify publishes the repository root using the settings in `netlify.toml`.

- Production branch: `main`
- Entry point: `index.html`
- Production domain: `systems.handgraafestates.com`
- Demo dashboard: https://demo.handgraafestates.com

## Updating the site

1. Edit `index.html`.
2. Commit the change to `main`.
3. Netlify automatically builds and publishes the new version.
4. Verify the production page on desktop and mobile.

## Domain setup

The Netlify primary domain is `systems.handgraafestates.com`. Its DNS CNAME record uses host `systems` and points to `estatehandgraafestates.netlify.app`.
