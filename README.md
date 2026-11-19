# RenderFM-Next — Project Page

Project page for **Feed-Forward Adaptive Gaussian Splatting for Interactive Medical Volume Rendering**.
Zhongpai Gao, Benjamin Planche, Meng Zheng, Anwesa Choudhuri, Terrence Chen, Ziyan Wu.

Live at https://gaozhongpai.github.io/renderfmnext/ — part of the [NDSplat](https://gaozhongpai.github.io/ndsplat/) line
(DDGS, 6DGS, 7DGS, UBS, dGS/dBS, Render-FM, XClipGS, FactorSplat, RenderFM-Next).

## Structure

```
index.html                 # single page
static/css/                # Bulma + shared NDSplat theme (ndsplat-theme.css)
static/js/ndsplat-nav.js   # shared nav + scroll reveal
static/images/             # teaser, pipeline, qualitative figures (from the paper)
static/videos/             # demo video
```

Fully static. Preview with `python3 -m http.server 8000`.

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(adapted from [Nerfies](https://nerfies.github.io)), licensed CC BY-SA 4.0.
