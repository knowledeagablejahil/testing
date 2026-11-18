# SABR splash screen — 1-second GitHub Pages test

A tiny standalone test of the approved emerald-green SABR splash design. It displays the original approved image (icon, صبر, SABR and loading bar) for approximately **one second** and then shows a test page with a **Replay 1-second splash** button.

## Test on your phone or computer via GitHub Pages

1. Create a new GitHub repository, such as `sabr-splash-test`.
2. Upload `index.html` and the **`assets` folder** to the repository root (do not upload the outer ZIP directly). Commit the files.
3. Open **Settings → Pages** in that repository.
4. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then Save.
5. When the GitHub Pages deployment is complete, open the URL shown under Pages. It usually resembles `https://USERNAME.github.io/sabr-splash-test/`.

For a private repository, GitHub Pages availability may depend on your plan/settings. A public test repository is sufficient because this demo contains no user data or secrets.

## Notes

- This is a **browser preview**, not an Android APK, and it does not modify the original SABR project.
- The loading progress bar is drawn in the preview image, **not a live download progress indicator**. It is intentionally only a visual mock-up.
- The code loads no third-party packages, has no API calls, and stores no data.
- Edit `SPLASH_DURATION_MS` in `index.html` to change the splash duration.
