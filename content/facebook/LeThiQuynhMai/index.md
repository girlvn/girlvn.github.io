---
title: "Image Gallery"
categories: ["big"]
images:
  - url: "https://raw.githubusercontent.com/girlvn/lethiquynhmai/refs/heads/main/120136370_434669340842806_731249933876844970_n.jpg"
    alt: "Image 1 Description"
  - url: "https://raw.githubusercontent.com/girlvn/lethiquynhmai/refs/heads/main/165963841_556637325312673_5150904363099115088_n.jpg"
    alt: "Image 2 Description"
  - url: "https://raw.githubusercontent.com/girlvn/lethiquynhmai/refs/heads/main/139590116_515173976125675_8943335205970849727_n.jpg"
    alt: "Image 3 Description"
---
# Image Gallery

<div class="gallery">
  {{ range .Params.images }}
    <div class="gallery-item">
      <img src="{{ .url }}" alt="{{ .alt }}" />
    </div>
  {{ end }}
</div>
