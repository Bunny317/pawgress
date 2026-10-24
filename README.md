# Pawgress v1

A mobile-first, Chinese-language cat behaviour training PWA. Includes 7-day plan, checklists, behavioural diary, 14-entry distance chart, JSON backup/restore, CSV export and downloadable recurring calendar events.

## Try locally

From this directory run `python3 -m http.server 8000`, then open http://localhost:8000 on your computer. On iPhone, publish to an HTTPS host for installability.

## Publish with GitHub Pages

1. Create a GitHub repository (e.g. `pawgress`).
2. Upload `index.html`, `manifest.webmanifest`, `icon.svg`, and `sw.js` to the repository root.
3. Open Settings → Pages → Build and deployment → Deploy from a branch → `main` / root → Save.
4. Open the resulting `https://YOURNAME.github.io/pawgress/` URL on iPhone in Safari.
5. Share → Add to Home Screen.

## Alternative: Netlify Drop

Upload the folder to https://app.netlify.com/drop/ (requires Netlify account or service availability), then open its HTTPS link in Safari and add to home screen.

## Data and reminders

Data is stored in browser localStorage only; it is not synced to cloud or ChatGPT. Export JSON backups regularly. Deleting site data may remove records. CSV exports diary observations. The downloadable ICS contains two recurring events at 09:00 and 19:00 local time, but import support varies by device/calendar app. For dependable notifications, configure repeating reminders directly in iOS Reminders.

## Safety

Keep training below fear threshold. Do not punish, shout, chase, force contact, or lure into unwanted touching. Separate cats for feeding. Consult a veterinarian if avoidance is sudden or severe.
