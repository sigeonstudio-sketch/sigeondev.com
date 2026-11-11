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

https://sigeonstudio-sketch.github.io/
