# Changelog

All notable changes to the Yoga Class Builder, newest first. The version number is also shown in the app header.

## 0.5.1 - 2026-10-30
- Once the app is installed, the install button turns into "Uninstall app" and shows how to remove it (browsers do not let a web app remove itself, so it shows the steps).

## 0.5.0 - 2026-10-28 (work in progress)
- You can now edit any pose card: open a pose, tap "Edit pose", and change its name, Sanskrit name, category, level, hold time, both sides, body areas, benefits, cues and cautions. "Reset to original" brings the built-in text back.
- Your pose edits sync between your devices when you are signed in.

## 0.4.0 - 2026-10-27 (work in progress)
- Colour theme button in the header: Auto (follows your phone), Light or Dark. Your choice is remembered on each device.
- Drag and drop to reorder poses and sections in the class: hold the dotted handle on the left of an item and move it. The up and down buttons are still there.
- Fixed the pose rows in the class running slightly off the right edge on phones, which cut off the times.
- The page header scrolls away on phones instead of staying pinned, giving more room for the class.
- The back button (or back swipe) now steps back through the app: it closes a pop-up or Teach mode first, then returns to the previous tab, instead of leaving the app. From the main Class screen it still leaves the app.

## 0.3.0 - 2026-10-27 (work in progress)
- Classes now sync between your devices. Use "Sign in to sync" (Google, same login as the Control Room). Changes appear on your other devices within a moment, and offline changes sync when you are back online. Without signing in the app still works and saves on the device.
- The first time you sign in on a device, its classes are uploaded and the ones from your other devices are downloaded, so you may see a second "Example class" to delete.

## 0.2.0 - 2026-10-27 (work in progress)
- Several classes are now easy to find and use: a class switcher and a "New class" button sit at the top of the Class view (the "My classes" tab is still there to open, duplicate or delete).
- New look: a pink, beige and brown palette for the app, the pose figures, the printed PDF and the app icon, in light and dark mode.

## 0.1.4 - 2026-10-27 (work in progress)
- Small note next to the version showing where the app is hosted (Cloudflare or GitHub Pages), so you can tell the copies apart.

## 0.1.3 - 2026-10-27 (work in progress)
- The "Install app" button is now always visible (unless the app is already installed). If the browser cannot show its own install prompt, it shows short steps for your browser instead. Shared install.js file used by all my apps.

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
