# Hidden Word

A Scripture memory app for your phone: your own verse list in any Bible version, built-in KJV verses, memory challenges, fill-in-the-blank quizzes, a Memory Drill, a Sword Drill, a Scripture Songs playlist and a daily calendar reminder.

## Files

- `index.html` – the whole app
- `apple-touch-icon.png`, `apple-touch-icon-precomposed.png` and `apple-touch-icon-120/152/167/180.png` – the iPhone and iPad home-screen icons in every size iOS asks for
- `icon-192.png`, `icon-512.png`, `manifest.webmanifest` – icons and settings for Android and "Add to Home Screen"
- `icon-1024.png` – a large copy of the icon for printing, sharing or an App Store listing
- `favicon.png` – the browser tab icon
- `.nojekyll` – tells GitHub Pages to serve the files as they are

## Putting it on GitHub Pages

1. Create a new repository on GitHub (for example `hidden-word`).
2. Upload every file in this folder to the top level of the repository, not inside a subfolder. The `.nojekyll` file may be hidden on your computer; it's optional.
3. In the repository, go to **Settings → Pages**, set **Source** to "Deploy from a branch," choose the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the app is live at `https://<your-username>.github.io/hidden-word/`.

## Adding it to an iPhone home screen

Open the site in **Safari**, tap the **Share** button, then **Add to Home Screen**.

If the icon shows as a gray letter or a screenshot instead:

1. Make sure every icon file is at the top level of the repository, next to `index.html`, not in a folder.
2. Wait a few minutes after uploading; GitHub Pages can take a moment to publish new files.
3. Delete the old home-screen shortcut (press and hold it, then **Remove App → Delete from Home Screen**).
4. In Safari, open the site, pull down to refresh, and add it to the home screen again.
5. If it still shows the old picture, go to iPhone **Settings → Apps → Safari → Clear History and Website Data**, then add it again.

## Notes

- Each person's verses, challenges and streak are saved in their own browser on their own phone.
- The **Add to iPhone Calendar** reminder works here in Safari.
- The **Sword Drill** looks up verses through Claude, so on this website it shows a short note instead of drawing verses. Everything else works.
