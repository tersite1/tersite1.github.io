---
order: 2
name: 3D Reconstruction of Yonsei Engineering Building
category: personal
tools: [3D Reconstruction, Point Cloud, Registration]
video: /assets/img/p-engineering.mp4
image: /assets/img/p-engineering.png
description: Complete 3D reconstruction of the Yonsei engineering building via NeRF and direct mobile scanning, fused through point-cloud registration.
---

## 3D Reconstruction of Yonsei Engineering Building

I reconstructed the Yonsei engineering building end to end: I generated NeRF-based 3D models, captured the structure by direct mobile scanning, and registered the two into a single, complete 3D model of the building.

### Approach
NeRF reconstruction from images alone gives dense visual detail but can drift geometrically over a large structure, while direct mobile LiDAR scanning gives accurate metric geometry but is sparser and slower to capture everywhere. I treated these as two views of the same building and registered them into one point cloud, using the mobile scan to correct the NeRF reconstruction's geometry while keeping its visual density.

### Why this matters
Most reality-capture pipelines commit to a single sensing modality and inherit its weaknesses. Fusing an image-based and a direct-scan reconstruction of the same structure is a small-scale version of the calibration and georeferencing problem that any multi-platform mapping system has to solve, treating acquisition, alignment, and the final model as one continuous problem rather than separate steps.

<figure class="pd-fig"><img src="/assets/img/g-eng-1.png" alt=""><figcaption>NeRF reconstruction of the building</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-eng-2.png" alt=""><figcaption>Direct mobile scan</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-eng-3.png" alt=""><figcaption>Registered, complete 3D model</figcaption></figure>

