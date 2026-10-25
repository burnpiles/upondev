# upon.dev

Stealth coming-soon page for upon.dev. Plain static files, no build step.

- `index.html` is the whole page (`?mode=original|strobe|void` previews the other tellings; `void` is the default).
- `vid/` holds the film (H.264 mp4 plus a webm fallback), `music/` the soundtrack, `img/` the still plates used if the video fails.

Deployed on Vercel straight from `main`, with framework preset "Other" and no build command.
