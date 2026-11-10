# Hidden Word

A Scripture memory app for your phone: your own verse list in any Bible version, built-in KJV verses, memory challenges, fill-in-the-blank quizzes, a Memory Drill, a Sword Drill, a Scripture Songs playlist and a daily calendar reminder.

## Files

- `index.html` – the whole app
- `apple-touch-icon.png` – the iPhone home-screen icon
- `icon-192.png`, `icon-512.png`, `manifest.webmanifest` – icons and settings for Android and "Add to Home Screen"
- `favicon.png` – the browser tab icon
- `.nojekyll` – tells GitHub Pages to serve the files as they are

## Putting it on GitHub Pages

1. Create a new repository on GitHub (for example `hidden-word`).
2. Upload every file in this folder to the top level of the repository, not inside a subfolder. The `.nojekyll` file may be hidden on your computer; it's optional.
3. In the repository, go to **Settings → Pages**, set **Source** to "Deploy from a branch," choose the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the app is live at `https://<your-username>.github.io/hidden-word/`.

## Adding it to an iPhone home screen

Open the site in **Safari**, tap the **Share** button, then **Add to Home Screen**. If the icon doesn't show, delete the home-screen shortcut, wait a few minutes for GitHub to finish publishing, and add it again.

## Notes

- Each person's verses, challenges and streak are saved in their own browser on their own phone.
- The **Add to iPhone Calendar** reminder works here in Safari.
- The **Sword Drill** looks up verses through Claude, so on this website it shows a short note instead of drawing verses. Everything else works.
