---
order: 8
name: Quad-Tiltrotor VTOL Search & Rescue Drone
category: drone-club
tools: [VTOL, UAV Design, Autonomous SAR, Aerospace]
image: /assets/img/p-vtol.gif
description: Joint 1st Place at the 23rd AAM Tech Challenge (KASA). A quad-tiltrotor VTOL for autonomous search and rescue, where I led the software.
---

## Quad-Tiltrotor VTOL Drone for Autonomous Search and Rescue

This is one of the achievements I'm proudest of. Our Yonsei Drone team won **Joint 1st Place at the 23rd AAM (Advanced Air Mobility) Tech Challenge**, hosted by the **Korea AeroSpace Administration (KASA)** in September 2025, with a quad-tiltrotor VTOL aircraft built for autonomous search and rescue. **I led the software** for the platform.

<figure class="pd-fig"><img src="/assets/img/g-vtol-3.png" alt=""><figcaption>The design render and the carbon-fiber prototype we built and flew</figcaption></figure>

### The aircraft
It is a fixed-wing and quad-tiltrotor hybrid: roughly a **2.4 m wingspan** with **four Ø406 mm tilting rotors**, so it lifts off and lands vertically like a multirotor but cruises efficiently like a plane. The airframe is carbon fiber, and the **center of gravity is adjustable** so it stays balanced through the hover-to-cruise transition (the subject of one of our patents). Underneath, it carries a dedicated **rescue module**: an onboard camera, an electric ducted fan (EDF), and a **dynamic hook** for picking up and releasing payloads on target.

<figure class="pd-fig"><img src="/assets/img/g-vtol-2.png" alt=""><figcaption>Airframe views and the four-rotor tilt layout with clearances</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-vtol-1.png" alt=""><figcaption>The rescue module: camera, EDF, and the dynamic release hook</figcaption></figure>

### My role: software
I owned the autonomous mission software end to end: the **VTOL transition logic** between hover and forward flight, **guidance and waypoint missions** for autonomous search, **onboard perception** that locates the target (for example, a red cross) in flight, and the automated **approach-and-release sequence** that delivers the rescue module. The telemetry and mission state you see in the flight footage above, waypoints, flight mode, altitude, and target lock, are driven by that software. It flew the full mission live at the competition, and the work was published at **KRoC 2026**.

<div style="display:flex; gap:.6rem; flex-wrap:wrap; margin:1.2rem 0;">
<a style="display:inline-block; font-size:.85rem; font-weight:700; padding:.5rem .95rem; border-radius:7px; border:1.5px solid #043361; color:#043361; text-decoration:none;" href="https://yonseidrone.notion.site/a9c169ae021445d0a5d95a083d69b1ad" target="_blank" rel="noopener">Project Page ↗</a>
<a style="display:inline-block; font-size:.85rem; font-weight:700; padding:.5rem .95rem; border-radius:7px; border:1.5px solid #043361; color:#043361; text-decoration:none;" href="https://engineering.yonsei.ac.kr/me/community/news.do?mode=view&articleNo=456983" target="_blank" rel="noopener">Yonsei News ↗</a>
<a style="display:inline-block; font-size:.85rem; font-weight:700; padding:.5rem .95rem; border-radius:7px; border:1.5px solid #043361; color:#043361; text-decoration:none;" href="https://www.instagram.com/yonsei_drone/" target="_blank" rel="noopener">Instagram ↗</a>
</div>

<div style="position:relative; padding-bottom:56.25%; height:0; margin:1.6rem 0; border-radius:.6rem; overflow:hidden;">
<iframe style="position:absolute; top:0; left:0; width:100%; height:100%;" src="https://www.youtube.com/embed/iyjVVylZR5Q" title="Yonsei Drone Demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
