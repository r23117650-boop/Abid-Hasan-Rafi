# Abid Hasan Rafi Portfolio — Vercel Fixed Package

This package is designed as a plain static HTML website to avoid common Vercel 404 causes related to missing build output or nested folders.

## Package contents
- `index.html` — entire website, CSS, animations, mobile navigation, metadata, and Person structured data.
- `vercel.json` — explicit static deployment configuration with a clean fallback to `index.html`.
- `robots.txt` — crawler instructions and sitemap location.
- `sitemap.xml` — homepage sitemap template.
- `README.md` — these instructions.

## Important: upload the files correctly
1. Download and extract this ZIP on your computer.
2. Open the extracted folder. You should see `index.html`, `vercel.json`, `robots.txt`, `sitemap.xml`, and `README.md` together.
3. Upload these files to the **root of the GitHub repository**, not inside another nested folder.
4. In Vercel, open the project connected to that repository.
5. In **Settings → Build and Deployment**, set Framework Preset to `Other`. Leave Build Command empty. Set Output Directory to `.` (or leave it blank if the Vercel interface detects the root static output automatically). Set Root Directory to the repository root.
6. In **Deployments**, redeploy the latest commit. Check that deployment status becomes `Ready`.
7. Open the production deployment URL from the Vercel dashboard. Then test `https://abid-hasan-rafi.vercel.app/`.

## If you still see 404
- Confirm `index.html` is visible at the repository root.
- Confirm the Vercel project is linked to the correct GitHub repository and branch.
- Open the latest deployment's build/deployment logs.
- In Settings → Domains, confirm `abid-hasan-rafi.vercel.app` is assigned to this project.
- Redeploy after changing settings.

## SEO setup
The page contains a title, meta description, canonical URL, Open Graph metadata, Person JSON-LD, semantic sections, and internal navigation. Replace the LinkedIn placeholder with your actual LinkedIn profile URL before publishing.
The sitemap and robots file already use `https://abid-hasan-rafi.vercel.app/`. Update them if your domain changes.

SEO setup cannot guarantee Google indexing or a particular ranking.
