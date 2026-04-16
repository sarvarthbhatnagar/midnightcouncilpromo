# Midnight Council promo site

Static landing page for the Midnight Council game (iOS and Android store links, roles, learn more).

## Store buttons (badges)

The page uses **official** badge artwork from Apple and Google (white App Store badge for dark backgrounds, standard Google Play badge), linked per each company’s marketing guidance. Badges load from `tools.applemediaservices.com` and `play.google.com`. Role art and the app icon stay in this repo.

## Deploy on Vercel

1. Push this repository to GitHub (if it is not already).
2. In [Vercel](https://vercel.com), choose **Add New Project** and import `sarvarthbhatnagar/midnightcouncilpromo`.
3. Preset: **Other** (or leave default). Root directory: `.` (repository root). No build command. Output is not used; `index.html` is served from the root.
4. Deploy. Vercel will serve `index.html` at `/` and static PNGs next to it.

### Local preview

Open `index.html` in a browser from this folder, or run any static server, for example:

```bash
npx serve .
```
