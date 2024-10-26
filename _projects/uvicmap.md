---
layout: page
title: UVicMap
description: Interactive, 3D Map of the University of Victoria
img: assets/img/uvicmap.jpg
importance: 1
category: work
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/uvicmap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Current development as of Oct 26, 2024. <a href="https://ma-graff.github.io/uvicmap/" target="_blank">Click here for the demo.</a>
</div>


This project is a 3D interactive map of the University of Victoria - aimed to help students navigate all of the buildings. The map uses MapLibre GL with MapTiler for 3D rendering, satellite overlay, and vector tiles, providing a highly visual and intuitive way to explore the campus. Designed with a rotating camera for dynamic viewing, users can explore building details, navigate, and enable geolocation to identify their current location on campus. Boundaries and zoom levels restrict panning outside the UVic area, maintaining focus on the university's layout.

**The next steps of development include:**

- **Improved Tile Hosting:** Seeking efficient hosting for high-performance tile loading.
- **Routing Features:** Integrating routing functionalities to assist users with wayfinding around campus.
- **Additional Features:** Adding overlays, dynamic building information, and enhanced interactivity.

This project aims to support UVic students and visitors by providing a visually engaging and interactive map experience.
