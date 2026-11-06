# ChainLab — Mini Blockchain for GitHub Pages

This is a static website made with HTML, CSS, and JavaScript. **No Python, Flask, Node.js, or installation is required.**

## Publish on GitHub Pages

1. Extract this ZIP file.
2. Open your existing GitHub repository.
3. Upload `index.html`, `README.md`, and `.nojekyll` into the repository's published root folder.
4. Commit the changes.
5. Open your GitHub Pages URL and refresh. It may take a minute or two to update.

If your Pages site currently displays the README, make sure `index.html` is in the exact folder configured as the Pages publishing source (often the repository root or `/docs`).

## Use the app

1. Enter sender, receiver, and amount.
2. Click **Add transaction**.
3. Click **Mine pending transactions**.
4. Click **Verify blockchain** to validate hashes and previous-hash links.
5. Click **Reset demo** to clear the local demo.

## Technologies

- HTML5, CSS3, vanilla JavaScript
- Browser Web Crypto API (SHA-256)
- Browser localStorage

## Educational limitations

This is a single-browser educational simulation, not a decentralized peer-to-peer network or real cryptocurrency. Data remains in the current browser's local storage and is not shared across devices. GitHub Pages serves the static files; it does not run a backend.
