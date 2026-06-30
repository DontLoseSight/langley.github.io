---
layout: page
title: MIT Motorsports
permalink: /photography/mit-motorsports/
gallery: photography/mit-motorsports
---

{% assign images = site.static_files | where_exp: "f", "f.path contains page.gallery" %}
<div class="gallery">
  {% for f in images %}{% if f.extname == '.jpg' or f.extname == '.jpeg' or f.extname == '.png' %}<img src="{{ f.path | relative_url }}" alt="{{ page.title }}" loading="lazy">
  {% endif %}{% endfor %}
</div>
