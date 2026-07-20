SAME GAME FOR IPAD — INSTALLABLE WEB APP
========================================

This folder contains the approved Same Game recreation packaged as an
iPad-friendly Progressive Web App (PWA). The game remains self-contained;
the additional files provide the Home Screen icon, standalone launch mode,
and offline use after the first successful visit.

FILES
-----
index.html                 The game and its touch/PWA integration
manifest.webmanifest       Home Screen name, colors, icons, and launch mode
sw.js                      Offline app-shell cache
icons/                     iPad and PWA icons

PUT IT ONLINE
-------------
Upload this whole folder, preserving the filenames and icons subfolder, to a
static HTTPS host such as GitHub Pages. A service worker cannot be installed by
opening index.html directly from the Files app.

INSTALL IT ON AN IPAD
---------------------
1. Open the hosted link in Safari while connected to the internet.
2. Wait for the game to appear, then tap Safari's Share button.
3. Tap "Add to Home Screen" and then "Add."
4. Launch Same Game from its new Home Screen icon.

The app opens without normal Safari browser controls. After the first online
visit has completed, the game, menus, icons, sound code, and saved local scores
remain available offline. iPadOS may wait for the first tap before allowing
sound; this is normal.

IPAD CONTROLS
-------------
Tap a removable tile group once to highlight it and display its MARK and POINT
value. Tap that same highlighted group a second time to remove it. The selected
tiles then disappear one by one with a matching buzzer pulse before gravity
settles the board. Tapping a different valid group moves the highlight; tapping
outside a removable group clears it. Tap Menu, Option, or Help to open the
original menus. Their touch targets become slightly larger on touch screens
while retaining the classic Windows appearance. The Size and Character
submenus are also tap-enabled. Normal and Large boards retain their original
aspect ratios and scale uniformly so the entire board remains visible.
