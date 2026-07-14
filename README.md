# huynguyen792.github.io

Personal academic homepage of **Dr Huy Nguyen** — Research Fellow, School of Electrical
Engineering & Robotics, Queensland University of Technology (SAIVT).

Live: **https://huynguyen792.github.io/**

## What this is
A single-page static site (plain HTML + CSS, no build step). GitHub Pages serves it directly.
`.nojekyll` disables Jekyll processing so files are published as-is.

## Structure
```
index.html          # the whole homepage
assets/
  style.css         # all styling (light/dark aware, responsive)
  avatar.svg        # monogram fallback used until a real photo is added
  favicon.svg
  cv.pdf            # one-page CV (public-safe; NOT the master CV with certificates)
.nojekyll
```

## To add a profile photo
Drop a square image at `assets/profile.jpg` (≈600×600). The page uses it automatically;
if it's missing, it falls back to the monogram avatar.

## To edit
All content is inline in `index.html` under clearly labelled sections
(`HERO`, `NEWS`, `PUBLICATIONS`, `DATASETS`, `AWARDS`, `SERVICE`, `CONTACT`). Edit, commit, push.
GitHub Pages redeploys within ~1 minute.
