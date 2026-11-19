# Alice Huang – photographer website

A one-page static site (no build step).

- `index.html` – the site. Open it directly or deploy it as is.
- `assets/` – images. Swap `wedding-01.png` or add more and reference them from `index.html`.
- `project/` – editable source for the Claude Design canvas. Not part of the deployed site (see `.vercelignore`).

## Deploy to Vercel

1. In Vercel, choose **Add New → Project** and import this repository.
2. Leave **Framework Preset** as *Other*, and leave the build command and output directory empty.
3. Click **Deploy**. Every push to `main` redeploys.

Or from the command line: `npx vercel --prod`.
