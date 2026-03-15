# Popora Official Website (`popora-site`)

This repository contains the official static website for **Popora**, a casual mobile bubble game for iPhone and Android.

It is designed to be simple, clean, and easy to deploy with **GitHub Pages**.

## Included Structure

- `index.html` — public landing page
- `privacy.html` — editable privacy policy for a mobile app using AdMob
- `support.html` — support page with contact and FAQ
- `404.html` — custom not-found page
- `app-ads.txt` — AdMob authorization file at site root
- `css/styles.css` — shared styles
- `js/main.js` — minimal shared script
- `assets/icons/` — icon files placeholder
- `assets/images/` — screenshots/images placeholder

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Open repository **Settings** → **Pages**.
3. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/ (root)`
4. Save and wait for GitHub Pages to publish.

Your site should be available at:
- `https://YOUR_USERNAME.github.io/popora-site/` (project site)
- or a custom domain if configured.

## Edit Before Publishing

Update these placeholders before making the site public:

- `REPLACE_WITH_SUPPORT_EMAIL`
- `REPLACE_WITH_ADMOB_PUBLISHER_ID`
- `REPLACE_WITH_APPLE_LINK`
- `REPLACE_WITH_ANDROID_PACKAGE`
- `REPLACE_WITH_STUDIO_NAME`
- `REPLACE_WITH_DEVELOPER_OR_STUDIO`
- `REPLACE_WITH_DATE`
- `REPLACE_WITH_CHILDREN_POLICY_STATEMENT`

You should also add real screenshots in `assets/images/` and update the media section in `index.html`.

## `app-ads.txt` Update

Open `app-ads.txt` and replace:

`pub-REPLACE_WITH_ADMOB_PUBLISHER_ID`

with your real AdMob publisher ID, keeping the rest of the line unchanged:

`google.com, pub-YOUR_REAL_ID, DIRECT, f08c47fec0942fa0`

## Common Content Updates

- Change support email in `privacy.html` and `support.html`.
- Update store links in `index.html`.
- Adjust app descriptions, FAQ, and legal text as needed.
- Update footer studio/developer name.

## Notes

- No heavy frameworks are used.
- This is GitHub Pages friendly static content.
- `app-ads.txt` is intentionally at the root for platform verification.
