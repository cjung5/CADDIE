# CADDIE — Project Page

Project page for **CADDIE: Compact Adaptive Detection-Driven Inference for Real-Time Golf Club Pose Estimation** (CVsports Workshop @ CVPR 2026).

Live: <https://cjung5.github.io/CADDIE/>

## Layout

```
.
├── index.html
├── figure/                 # all images used on the page
└── static/
    ├── css/index.css
    ├── pdfs/CADDIE.pdf     # paper, linked from the Paper button
    └── videos/             # drop a demo video here
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy on GitHub Pages

1. Push these files to the **root** of <https://github.com/cjung5/CADDIE> on the `main` branch.
2. **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `/ (root)`**.
3. Wait ~1 minute, then visit <https://cjung5.github.io/CADDIE/>.

## Adding a demo video

1. Save it as `static/videos/caddie_demo.mp4`.
2. In `index.html`, find the Video section and uncomment the `<video>` block.

## Credits

Template adapted from [Nerfies](https://github.com/nerfies/nerfies.github.io) (CC BY-SA 4.0).
