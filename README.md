# The Healing Trails — website

Static landing page for The Healing Trails, India's first sustainability-focused
trekking company, founded by Rashmi Singh and Sahil Kesharwani.

## What it does

A single, responsive landing page with a cinematic mountain hero and a founders
section. Pure HTML + CSS with a tiny bit of vanilla JavaScript for scroll
reveals — no build step, no dependencies.

## Files

| File         | Purpose                                  |
|--------------|------------------------------------------|
| `index.html` | Page markup                              |
| `style.css`  | All styling                              |
| `assets/`    | Your photos (see below)                  |

## Adding your photos

Photos are wired up already. Just drop the files into `assets/` with these exact
names and they appear automatically — **no code changes needed**:

| File                | Shows as                            |
|---------------------|-------------------------------------|
| `assets/hero.jpg`   | Full-screen mountain background     |
| `assets/rashmi.jpg` | Rashmi Singh's photo                |
| `assets/sahil.jpg`  | Sahil Kesharwani's photo            |

Until a file exists, a designed placeholder is shown (a gradient sky for the
hero, and the founder's initials for each photo).

**Tips for best results**
- `hero.jpg` — wide/landscape, at least ~2000px across.
- `rashmi.jpg` / `sahil.jpg` — square-ish; they're cropped to a circle.

## Founder social links

Each founder tile links to Instagram and YouTube. To set the destinations, open
`index.html` and replace the placeholder values inside the `href="..."` of the
four links (the blocks are marked with `▼▼▼ RASHMI'S LINKS ▼▼▼` and
`▼▼▼ SAHIL'S LINKS ▼▼▼`):

| Placeholder to replace              | Put the full profile URL, e.g.            |
|-------------------------------------|-------------------------------------------|
| `REPLACE_WITH_RASHMI_INSTAGRAM`     | `https://www.instagram.com/rashmi.handle` |
| `REPLACE_WITH_RASHMI_YOUTUBE`       | `https://www.youtube.com/@rashmi.channel` |
| `REPLACE_WITH_SAHIL_INSTAGRAM`      | `https://www.instagram.com/sahil.handle`  |
| `REPLACE_WITH_SAHIL_YOUTUBE`        | `https://www.youtube.com/@sahil.channel`  |

Replace the **entire** `href` value with the complete URL. Links open in a new
tab.

## Run locally

Just open `index.html` in a browser. Or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Prerequisites

A modern web browser. Nothing else to install.
