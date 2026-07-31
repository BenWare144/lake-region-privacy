# Lake Region Consulting — Privacy Policy

A single static page (`index.html`) hosted with GitHub Pages, used as the
privacy-policy URL for the "Athelas Insights Helper" Chrome extension.

This folder is meant to live at `C:\Users\Ben\Downloads\mom_ahk_script\lake-region-privacy`
(move it there if it isn't already — the whole folder, including its hidden `.git`).

## Publish (one time)
1. Create a **new public** repo on GitHub named `lake-region-privacy` (empty — no README).
2. Open a terminal in this folder and push:
       cd "C:\Users\Ben\Downloads\mom_ahk_script\lake-region-privacy"
       git remote add origin https://github.com/BenWare144/lake-region-privacy.git
       git push -u origin main
3. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch →
   Branch: `main` / `/ (root)` → Save.**
4. Wait ~1 minute. Your policy URL will be:
       https://benware144.github.io/lake-region-privacy/
   Paste that into the Chrome Web Store **Privacy** tab.

To update the policy later: edit `index.html`, commit, and `git push` — Pages redeploys automatically.
