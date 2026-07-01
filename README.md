# Online Quran Academy

This is a simple static website for an online Quran academy.

## Deploy to GitHub + Netlify

1. Create a GitHub repository and push the project.
2. Open Netlify and choose "Add new site" → "Import an existing project".
3. Connect your GitHub repository.
4. Set these deployment settings:
   - Build command: leave empty
   - Publish directory: `.`
5. Deploy the site.

## Notes
- The project is a static site, so no build step is required.
- The included `netlify.toml` file helps Netlify detect the correct publish directory.
- For automatic deploys on every push to `main`, add these GitHub secrets:
  - `NETLIFY_AUTH_TOKEN`
  - `NETLIFY_SITE_ID`
