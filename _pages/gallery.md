---
layout: splash
classes: wide
permalink: /gallery/
title: "Pictures"
sidebar:
  nav: "side"
header:
  overlay_image: /assets/images/banner-art.jpg
toc: false
---

<section class="page__content">

  <div class="image-gallery">
    {% assign gallery_images = site.static_files | where: "path", "/assets/gallery" %}
    {% for img in site.static_files %}
      {% if img.path contains '/assets/gallery/' %}
        <figure>
          <a href="{{ img.path | relative_url }}">
            <img src="{{ img.path | relative_url }}" alt="">
          </a>
        </figure>
      {% endif %}
    {% endfor %}
  </div>
</section>