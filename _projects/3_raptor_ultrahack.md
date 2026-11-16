---
layout: page
title: RAPTOR @ UltraHack 2026
description: Fully autonomous indoor search-and-detect drone
img: assets/img/projects/ultrahack_path.gif
importance: 3
category: research
github: https://github.com/akashshingha850/ultrahack2026
---

**R**eal-time **A**utonomous **P**atrol for **T**actical **O**peration & **R**econnaissance, built by Team 9 for the **UltraHack 2026** challenge at Nokia Arena.

Starting from a random point in a ~60 × 30 m GPS-denied arena, the drone autonomously finds a **smoke** plume (primary target) plus **humans** and **fire** (secondary targets), flies to the source, inspects it and returns to launch. All perception and mission logic runs on board, with no cloud dependency.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/ultrahack_run.gif" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/ultrahack_path.gif" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Left: competition flight, YOLO-annotated onboard view (sped up). Right: dynamic path planning.</div>

Team: Akash Bappy, Taufiq Ahmed, Abu Taher, Sujith Srinivasan. [Source and results on GitHub →](https://github.com/akashshingha850/ultrahack2026)
