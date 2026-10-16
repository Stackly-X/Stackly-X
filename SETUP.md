# Upload this animated GitHub README

This package contains an **actual animated GIF banner**, not a static SVG. The moving text, live pipeline particles and progress effects are embedded as GIF frames and work in GitHub README images.

## Replace your current GitHub profile README

1. Open https://github.com/mzbit8890/mzbit8890 (replace the username if different).
2. Click **Add file → Upload files**.
3. From this extracted ZIP, drag **README.md** and **assets/portfolio-animated.gif** into the upload area. Keep the folder structure exactly as `assets/portfolio-animated.gif`.
4. Commit the changes. If GitHub doesn't allow overwriting the existing README through Upload files, click on README.md → pencil icon (Edit), then replace its contents with the new file's text and commit separately. Upload the GIF to `assets/`.
5. Visit https://github.com/mzbit8890 to see it move. Refresh if you see an older cached version.

`assets/portfolio-header.svg` is your old static banner and is kept only as a fallback. The new README uses `portfolio-animated.gif`.

The animation loops every ~6.8 seconds. It uses no third-party animation hosting service and needs no GitHub Actions.
