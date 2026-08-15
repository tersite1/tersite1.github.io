---
order: 11
name: Landslide Risk Digital Twin
category: personal
tools: [Digital Twin, Sensor Fusion, Remote Sensing]
image: /assets/img/p-landslide.png
description: A digital twin for landslide risk, simulating rainfall scenarios from normal precipitation to flood-induced landslides.
---

## Landslide Risk Digital Twin

A digital twin for landslide risk assessment. I modeled a target region (Ansan) as a scaled physical model and simulated rainfall scenarios, from normal precipitation to flood-induced landslides, mapping real catchment volumes onto the model to reason about flood and landslide risk.

### Approach
I surveyed the target terrain and rebuilt it at scale, preserving the real catchment geometry so that water introduced onto the model behaves consistently with runoff on the actual site. By stepping rainfall intensity from normal precipitation up to flood-level events, the model reveals which slopes and drainage paths transition from stable to failure-prone first, well before that intensity is ever observed in the field.

### Why this matters
Landslide-prone terrain is expensive and slow to instrument directly, and post-hoc mapping only shows where a slope already failed. A physical digital twin lets risk be probed proactively, under rainfall conditions that haven't happened yet, so mitigation can be prioritized before a failure occurs rather than after.

<div style="margin:1.2rem 0;">
<a style="display:inline-block; font-size:.85rem; font-weight:700; padding:.5rem .95rem; border-radius:7px; background:#043361; color:#fff; text-decoration:none;" href="/assets/files/landslide-technical-report.docx">See our technical report ↓</a>
</div>

<figure class="pd-fig"><img src="/assets/img/g-land-1.png" alt=""><figcaption>Scaled physical model of Ansan with rainfall scenarios</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-land-2.png" alt=""><figcaption>Flood and landslide risk analysis</figcaption></figure>

