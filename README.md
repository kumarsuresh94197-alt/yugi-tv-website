# YUGI TV website

A mobile-friendly starter landing page for the YUGI TV Android app.

## Publish on GitHub Pages
1. Create a **public** GitHub repository named `yugi-tv-website`.
2. Upload `index.html` to the repository root and commit it.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait a few minutes. Your site URL will look like `https://YOUR-USERNAME.github.io/yugi-tv-website/`.

## Add your APK download link
1. Publish your APK through **GitHub → Releases → Create a new release**.
2. Attach your `.apk` file to the release and publish it.
3. Copy the APK asset download link.
4. Edit `index.html`, find `id="downloadBtn"` and replace `https://github.com/` with your APK link. Change the button text from `APK coming soon` to `Download APK`.
5. Commit the change. GitHub Pages will update automatically.

Only distribute APKs and streams you own or have permission to distribute. GitHub Pages hosts static websites; it does not build or host your Android app itself.
