---
layout: page
title: MIT Motorsports — A-Arms
permalink: /projects/mit-motorsports-aarms/
---

CAD designed A-Arms (structural suspension members) in Siemens NX for our 2024 Formula SAE car.

- Investigated composite suspension arm design and leading efforts to substitute 4130 steel tubes with roll-wrapped carbon fiber in 2025, validating a CF-aluminum insert bond using Instron testing
- Co-hosted three A-Arm design reviews, leading material and overall architecture selection
- Each A-Arm features uniquely sized 4130 steel tubes welded to a waterjet steel connection joint
- Collaborated with the uprights team to package the camber adjust, A-Arm, and pull rod systems

Withstood 400km of testing and Formula SAE competition at Michigan International Speedway.

{% assign images = site.static_files | where_exp: "f", "f.path contains 'projects/mit-motorsports-aarms'" %}
<div class="gallery">
  {% for f in images %}{% if f.extname == '.jpg' or f.extname == '.jpeg' or f.extname == '.png' %}<img src="{{ f.path | relative_url }}" alt="MIT Motorsports A-Arms" loading="lazy">
  {% endif %}{% endfor %}
</div>
