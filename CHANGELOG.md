# Changelog

All notable changes to the Yoga Class Builder, newest first. The version number is also shown in the app header.

## 0.1.2 - 2026-10-26 (work in progress)
- Now hosted on Cloudflare at its own web address, so it no longer clashes with other apps installed from GitHub Pages. Fresh install needed; classes saved on the old address do not carry over.
- App identity set for the new address.
- Added a Cloudflare deploy configuration (wrangler.jsonc) so the app can be hosted on Cloudflare as well as GitHub Pages. No change to the app itself.

## 0.1.1 - 2026-10-26 (work in progress)
- Gave the app a fixed identity in its manifest (id and start address) so browsers do not confuse it with an earlier or stale install.

## 0.1.0 - 2026-10-25 (work in progress)
- First standalone, installable version, converted from the claude.ai page.
- App icon and header carry a WIP mark.
- Classes are saved on the device (browser storage). No account or sync yet.
- PDF export works offline (jsPDF is bundled with the app).
- Installable as an app with an offline cache.
