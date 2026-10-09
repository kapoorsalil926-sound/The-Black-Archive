# THE BLACK ARCHIVE — Birthday Escape Room

A mobile-friendly static website for GitHub Pages. No build tools, frameworks, paid hosting, or backend required.

## Files
- `index.html`
- `style.css`
- `script.js`
- `assets/memory.jpg` — add your chosen photo here

## Add the photo puzzle image
1. Choose a photo you both love. A square image works best.
2. Rename it `memory.jpg`.
3. Upload it into the `assets` folder in your repository.
4. Keep the file path exactly `assets/memory.jpg`, or change `photoPath` in `script.js`.

## Final PIN
The current final clue derives **1327**:
- First date, 21st → final digit `1`
- First kiss, 3rd → final digit `3`
- First conversation month, February → `2`
- Official relationship day, 17th → final digit `7`

`SETTINGS.physicalLockCode` is currently set to `"1327"`. Set the physical lockbox to this code, or deliberately edit `deriveCode()` and `physicalLockCode` together.

This is a fun game, not secure authentication: client-side JavaScript can be inspected by a determined person. The physical lockbox is the real barrier.

## Publish free with GitHub Pages
1. Create a new **public** GitHub repository, e.g. `birthday-archive`.
2. Upload `index.html`, `style.css`, `script.js`, and the `assets` folder containing `memory.jpg`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then press **Save**.
6. After it publishes, the URL will look like `https://YOUR-USERNAME.github.io/birthday-archive/`.

No terminal, package install, or build command is needed. Every commit republishes the static site.

## Test flow
- Quote blanks in order: `deaf`, `entire`, `voice`, `listening`, `breathe`
- Canvas dates: `05-02-22`, then `17-03-22`
- Timeline order: 05-02-22 → 17-03-22 → 21-03-22 → 03-04-22 → 13-05-22 → 27-06-22 → 14-07-23 → 31-07-23
- Restaurant: `Rigveda`; dish: `Paneer Peshawari`
- Answer the multiple-choice questions, reconstruct the image, then solve the final code `1327`.

## Privacy
Anyone with the public URL can open the website. Do not put sensitive information into the site. It does not collect, save, or transmit her answers.
