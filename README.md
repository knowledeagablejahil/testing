# SABR — Minimal 1-second splash test

A single-page, dependency-free visual test for GitHub Pages.

- Matte near-black background
- Emerald geometric logo, with Arabic **صبر** and English **SABR**
- No decorative hills, glow, gradients, or loading bar
- Automatic fade into the test page after 1 second
- Replay button on the test page
- Works offline; no extra images or packages required

## Update the existing Codespaces test repo

1. Upload the ZIP to the repository root, then in the Codespaces terminal run:

   ```sh
   unzip -o SABR_Minimal_1_Second_Splash_Test.zip -d .
   ```

2. Commit and push:

   ```sh
   git add index.html README.md
   git commit -m "Simplify SABR splash screen"
   git push
   ```

3. Refresh the GitHub Pages URL (or use the Codespaces preview). If changes appear stale, force refresh.

If previewing locally, run `python3 -m http.server 8000` from the repository root, and open port 8000 under **Ports**.

This changes only the test page. It does **not** modify the production Android application.
