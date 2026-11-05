# K!SH EPK — starter project

This is the first working website scaffold for the K!SH artist EPK.

## What is included
- Astro static website
- Traditional electronic-music EPK layout with restrained South Asian geometric cues
- Mobile-responsive styling
- SoundCloud embed support
- Pages CMS configuration (`.pages.yml`)
- Editable artist profile, featured mix and event-credit content

## Before publishing
1. Replace the placeholder booking email in `src/content/site.json`.
2. Replace the Instagram URL.
3. Replace the example biography with the approved final copy.
4. Replace the sample mix URL with the exact SoundCloud mix URL you want embedded.
5. Add your own images to `public/media/` named `kish-hero.jpg` and `kish-press.jpg`.
6. Remove or replace the example event credit. Only publish confirmed credits.
7. Review all copy and links on mobile and desktop.

## Run locally (optional)
Install Node.js LTS, then open a terminal in this folder and run:

```bash
npm install
npm run dev
```

Astro will show a local preview address, usually http://localhost:4321.

To check the production build:

```bash
npm run build
```

## GitHub upload
Create a new public GitHub repository named `kish-epk`.
Upload the contents of this folder (not the containing folder) to the repository root.

## Pages CMS
1. Visit https://app.pagescms.org/
2. Sign in with GitHub and grant access to the `kish-epk` repository.
3. Pages CMS reads `.pages.yml` from the repository root.
4. Edit Artist profile, DJ mixes and Selected performances.
5. Uploaded media is stored in `public/media`.

## Cloudflare deployment
Cloudflare's product labels and dashboard may change. For a static Astro project, use the current Cloudflare Pages / Workers Builds Git integration for the GitHub repository. If using the Pages setup flow, use:
- Build command: `npm run build`
- Build output directory: `dist`
- Production branch: `main`

Connect GitHub to Cloudflare and choose this repository. Cloudflare will build and deploy on commits.

Official guide: https://developers.cloudflare.com/pages/framework-guides/deploy-an-astro-site/

## Important
- This is a starter, not a finished press kit. Replace placeholders before sharing with promoters.
- No booking form backend is configured; the booking button opens an email draft.
- A custom domain costs extra. The initial hosted subdomain can be free.
- Do not upload private phone numbers, home addresses or personal documents.
