---
permalink: /beyond-the-lab/
title: "Exploring mountains, cities, and the stories in between."
author_profile: true
---
<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}

.gallery img {
  width: 300px;
  border-radius: 8px;
}
</style>
<div class="gallery">
{% for i in (1..17) %}
  <img src="/assets/images/{{ i }}.jpg" alt="">
{% endfor %}
</div>
