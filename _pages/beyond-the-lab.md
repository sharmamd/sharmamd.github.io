---
permalink: /beyond-the-lab/
title: "Exploring mountains, cities, and the stories in between."
author_profile: true
---
<style>
.gallery {
  column-count: 2;
  column-gap: 10px;
}

.gallery img {
  width: 100%;
  height: auto;
  margin-bottom: 20px;
  border-radius: 12px;
  break-inside: avoid;
}
</style>

<div class="gallery">
{% for i in (1..17) %}
  <img src="/images/{{ i }}.jpg">
{% endfor %}
</div>
