# Jackpot — Roblox Animator Portfolio

Static one-page portfolio. No build step, no dependencies.

## Put it online with GitHub Pages

1. Create a new repository on GitHub (public).
2. Upload everything in this folder — `index.html`, `videos/`, `posters/`, `README.md` — keeping the folder structure.
3. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. A minute later the site is live at `https://YOURUSERNAME.github.io/REPONAME/`.

Naming the repo `YOURUSERNAME.github.io` instead gives you `https://YOURUSERNAME.github.io/`.

## Things to change before publishing

- `index.html`, contact section: replace `YOUR@EMAIL.COM`, `YOUR_ID` (Discord) and `YOUR_HANDLE` (X).
- `index.html`, bottom script: the `clips` list holds the title, one-line note and duration for each video. Edit the text there to name the real games and roles — placeholders are in now.
- To drop a clip, delete its line from `clips`; to add one, put the `.mp4` in `videos/`, a still in `posters/` with the same name, and add a line.
- The hero video is `videos/hero-duo-scene.mp4`. Swap the filename in the script to feature a different clip.

## Size note

The videos total ~55 MB. That's fine for GitHub (the hard limit is 100 MB per file), but if the repo grows past a few hundred MB, host the videos on YouTube or Streamable and embed them instead.
