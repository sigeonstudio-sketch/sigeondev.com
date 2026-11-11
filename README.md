# Sigeon Dev.

A gaming destination.

## Website

The site is plain static HTML/CSS/JS - no build step, no dependencies.

```
index.html          # the site
assets/logo.png     # logo
```

Serve it locally with any static server, e.g.:

```bash
python -m http.server 8000
```

The game library is stored in the browser under the `sigeonGames` localStorage key,
so it is per-browser rather than shared between visitors.

## Live site

https://sigeonstudio-sketch.github.io/home/

The published site is served from the `sigeonstudio-sketch.github.io` user-site
repository, which keeps the site under the `/home/` path. This repository
(`sigeondevwebsite`) holds the source and also publishes to
https://sigeonstudio-sketch.github.io/sigeondevwebsite/ as a fallback.
