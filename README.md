# Ben-inv

**Ben OS** is a personal command-centre dashboard in one file (`index.html`). Open it in any browser; there's nothing to install.

- **Metro map:** each project is a coloured line and each milestone is a station. Tap a station to tick it off.
- **Briefing headline:** how many stops you've reached across all lines, plus the line closest to finishing.
- **Command line:** `add <task> #line`, `note <text>`, `focus <minutes> #line`, `done <n>`, `next`, `brief`, `undo`, `help`.
- **Tasks, focus timer, a 7-night habit grid (post a clip, code, train) and notes.** Nights roll over at 6am.
- **Backup:** data is saved in your browser. Use "Back up or restore your data" to copy it out or load it back in.

Lines: `#clips`, `#python`, `#invest`, `#fit`. You can add or delete stations from the line panel.

## Install it as an app

Ben OS is a web app: once it's hosted you can add it to your home screen. It then opens full screen with its own icon and keeps working offline.

1. Merge the pull request into `main`.
2. GitHub Pages needs a public repo on the free plan: **Settings → General → Danger Zone → Change visibility → Public**. Only the code becomes public. Your tasks and notes stay on your phone.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)` → Save.**
4. After a minute the app is live at `https://dp25mw6gbc-jpg.github.io/Ben-inv/`.
5. Open that link on your phone:
   - **Android (Chrome):** ⋮ menu → **Install app** (or **Add to Home screen**).
   - **iPhone (Safari):** Share → **Add to Home Screen**.
