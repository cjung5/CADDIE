# CADDIE — Project Page

Project page for **CADDIE: Compact Adaptive Detection-Driven Inference for Real-Time Golf Club Pose Estimation** (CVsports Workshop @ CVPR 2026).

Live page: <https://cjung5.github.io/CADDIE/> (after GitHub Pages is enabled — see below).

## Repository layout

```
.
├── index.html              # the project page
├── README.md
├── figure/                 # all images / figures used on the page
└── static/
    ├── css/index.css       # custom styling on top of Bulma (loaded from CDN)
    ├── js/                 # (currently empty)
    ├── pdfs/CADDIE.pdf     # paper PDF served from the site
    └── videos/             # drop a demo video here later
```

## Local preview

From this directory:

```bash
python3 -m http.server 8000
```

then open <http://localhost:8000>.

## Publishing to GitHub Pages

1. Push the contents of this folder to the **root** of the `main` branch of
   <https://github.com/cjung5/CADDIE>.
2. On GitHub: **Settings → Pages → Build and deployment**
   - Source: *Deploy from a branch*
   - Branch: `main` / folder: `/ (root)`
3. Wait ~1 min and visit <https://cjung5.github.io/CADDIE/>.

## Adding a demo video later

1. Drop the file at `static/videos/caddie_demo.mp4`.
2. In `index.html`, find the `<!-- ===== VIDEO (placeholder) ===== -->` block
   and uncomment the `<video>` element (the poster currently points to `figure/teaser.png`).

## Credits

Template adapted from the [Nerfies](https://github.com/nerfies/nerfies.github.io) project page (CC BY-SA 4.0).
