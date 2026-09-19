# Jackpot — Roblox Animator Portfolio

This is my portfolio site. Static page, no build step, no dependencies — just open `index.html` or host it as-is.

## How I put it online with GitHub Pages

1. Made a new repo on GitHub (public).
2. Uploaded everything in this folder — `index.html`, `videos/`, `posters/`, `README.md` — keeping the folder structure.
3. Went to **Settings → Pages → Build and deployment → Source: Deploy from a branch**, set branch to `main`, folder to `/ (root)`, then hit Save.
4. A minute later it was live at `https://YOURUSERNAME.github.io/REPONAME/`.

If I name the repo `YOURUSERNAME.github.io` instead, I get the shorter `https://YOURUSERNAME.github.io/`.

## Stuff I need to update

- The Discord link and handle are already mine — no email, no Twitter, Discord's the only way to reach me.
- In `index.html`, bottom of the script, there's a `clips` list — one line per video with its id and duration. That's what feeds the grid. No captions show on the site anymore, but I still keep the note text in the code for my own reference.
- To drop a clip: delete its line from `clips`. To add one: drop the `.mp4` in `videos/`, a still with the same name in `posters/`, then add a line.
- The hero video is `videos/hero-duo-scene.mp4`. If I want a different clip up front, I just swap the filename in the script.

## Size note

All my videos together are ~55 MB, well under GitHub's 100 MB-per-file limit. If I keep adding clips and this repo gets into the hundreds of MB, I'll move the videos to YouTube or Streamable and embed them instead of hosting them directly.
