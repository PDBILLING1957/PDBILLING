# PD Billing PWA — GitHub Pages

This is the GitHub Pages-ready package for PD Billing PWA v10.

## Files
- `index.html` — application
- `manifest.json` — PWA metadata
- `sw.js` — offline service worker
- `icon.svg` — app icon
- `.nojekyll` — prevents GitHub Pages/Jekyll processing

## Publish
1. Create a GitHub repository.
2. Upload **all files in this folder to the repository root** (do not upload the containing folder itself).
3. In GitHub: **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. GitHub will publish the site at the repository Pages address.

GitHub Pages is static hosting. The billing database remains local on each device; no customer/invoice database is uploaded to GitHub by this package.

## Important
The app is currently an audit build. Real iPhone/iPad testing and final transaction sign-off are still required before production use.
