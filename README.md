# Midnight Council promo site

Static landing page for the Midnight Council game (iOS and Android store links, roles, learn more).

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
