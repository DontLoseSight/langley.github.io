---
layout: page
title: FIRST Robotics Competition
permalink: /projects/first-robotics/
---

Designed the entirety of our 2023 competition robot in SOLIDWORKS.

- Fully custom 2DoF arm driven by a planetary + chain reduction and supported by gas shocks to counteract arm mass
- Pneumatically actuated wrist/game piece manipulator with custom gear profile to ensure parallel actuation
- 3D printed wrist failure point to prevent bending of 6061 aluminum arm members
- Custom potentiometer mounting using herringbone gears to reduce backlash, allowing for accurate measurement of shoulder and elbow position

Achieved best performance in 8-year team history, including first district event win as an offensive robot.

{% assign images = site.static_files | where_exp: "f", "f.path contains 'projects/first-robotics'" %}
<div class="gallery">
  {% for f in images %}{% if f.extname == '.jpg' or f.extname == '.jpeg' or f.extname == '.png' %}<img src="{{ f.path | relative_url }}" alt="FIRST Robotics" loading="lazy">
  {% endif %}{% endfor %}
</div>
