# yerdana2002.github.io

Personal site and project index — served with GitHub Pages at
**https://yerdana2002.github.io**.

> Template in progress. Descriptions and screenshots below are placeholders to be
> replaced with full write-ups in each project's own repo.

## Projects

### [Canvas AI Assistant](https://github.com/Yerdana2002/canvas-ai-assistant)
An AI assistant for the Canvas LMS that takes the repetition out of course
administration. Instructors describe a change in chat or a form; the assistant drafts
it, shows a preview, and only publishes after approval.

`React` `FastAPI` `PostgreSQL` `LLM`

<!-- TODO: screenshot, feature list, setup instructions -->

---

### [Robustness Analysis of LiDAR-based 3D Object Detection](https://github.com/Yerdana2002/adv-robustness-analy-3d-od)
Adversarial attack and evaluation pipeline for LiDAR-based 3D object detection in
autonomous driving, built on MMDetection3D. Benchmarks FGSM, PGD, IoU-S, and LiDAttack
against CenterPoint, PointPillars, PillarNeSt, and FocalFormer3D on nuScenes.
Accompanies the ECCV 2026 paper.

`PyTorch` `MMDetection3D` `nuScenes` `Adversarial ML`

- [Paper (arXiv:2607.02074)](https://arxiv.org/abs/2607.02074)
- [Project page](https://tmdt-buw.github.io/adv-robustness-analy-3d-od/)

<!-- TODO: note your specific contribution, add result figures -->

---

### [SoccerNet Jersey Number Recognition](https://github.com/Yerdana2002/Soccernet-jersey-number-recognition)
Tracklet-level jersey number recognition for broadcast soccer video, chaining player
detection, re-identification, pose estimation, legibility classification, and scene text
recognition. Fine-tuned PARSeq with synthetic crops for rare numbers reaches **93.04%**
tracklet accuracy on the SoccerNet test set.

`PyTorch` `PARSeq` `SoccerNet` `SLURM`

<!-- TODO: demo samples, pipeline diagram -->

## Repo layout

```
index.html    # the site — one file, no build step
assets/       # screenshots, CV, and other static files
```

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publishing

Push to `main`; GitHub Pages serves the site from the repository root
(Settings → Pages → Source: Deploy from a branch → `main` / `/root`).

## TODO

- [ ] Fill in the tagline, About paragraph, and contact links in `index.html`
- [ ] Add screenshots to `assets/` and swap the `.thumb` placeholders for `<img>` tags
- [ ] Add LinkedIn, email, and CV links
- [ ] Write full descriptions in each project repo, then trim these to summaries
