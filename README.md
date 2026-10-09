# Reza & Dela — What should we eat?

Single-page random restaurant picker (EN/فارسی). Plain HTML, no build step.

## Website (GitHub Pages)
1. Upload everything in this folder to a new GitHub repo (keep `.github/`).
2. Repo → Settings → Pages → Deploy from branch → `main` / root → Save.
3. Your site: `https://<username>.github.io/<repo>/`

## Android (installable)
- **Quick:** open the site in Chrome on Android → ⋮ → *Add to Home screen / Install app*.
- **APK:** repo → Actions → *Build Android APK* → Run workflow → download `reza-dela-apk` (debug APK; enable "install unknown apps" to sideload).
- Play Store needs a signed release build (AAB) — see Capacitor docs.

## Edit
- Background / YouTube link: `CONFIG` at the top of the script in `index.html`.
- Restaurants: `RAW` array / `DataSource.list()` in `index.html`.
