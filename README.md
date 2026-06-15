# Retirement Planner (TH / EN / JA) 🇹🇭

## What's new in this version
- Per-phase EXPENSE BREAKDOWN on the Life tab: each life stage now shows
  housing, food, utilities, healthcare & insurance, transport, leisure &
  travel, and caregiver & misc — with amounts in THB and % share, plus a
  visual bar for each category.
- Language switcher (TH / EN / JP), auto-detects device language, choice saved locally.
- All text, charts, and checklists fully translated.

## Deploy to GitHub Pages
1. Go to github.com -> New repository (Public)
2. Upload all files in this folder (index.html, manifest.json, sw.js, icon-192.svg, icon-512.svg)
3. Settings -> Pages -> Source: Deploy from a branch -> main -> / (root) -> Save
4. Wait 1-2 minutes, open https://[username].github.io/[repo]/

## Updating an existing GitHub Pages site
1. Open index.html in your repo, click the pencil (Edit) icon
2. Select all, delete, paste the new content from this index.html
3. Commit changes
4. Do the same for sw.js (cache version bumped to v3 so updates apply)
5. If installed as a PWA, close and reopen the app to pick up the update

## Install on Android
1. Open the URL in Chrome
2. Tap ⋮ -> "Add to Home screen" / "Install app"

## Notes
- Works offline after first load (Service Worker caches everything)
- No data is sent anywhere — 100% local
