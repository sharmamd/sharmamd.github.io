---
permalink: /beyond-the-lab/
title: "Exploring mountains, cities, and the stories in between."
author_profile: true
---
<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 20px;
}

.gallery img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 8px;
}
</style>

<div class="gallery">
{% for i in (1..17) %}
  <img src="/images/{{ i }}.jpg">
{% endfor %}
</div>
