---
permalink: /beyond-the-lab/
title: "Exploring mountains, cities, and the stories in between."
author_profile: true
---
<style>
.gallery {
  display: flex;
  flex-wrap: wrap: wrap;
  gap: 15px;
}

.gallery img {
  width: 400px;
  border-radius: 10px;
}
</style>
<div class="gallery">
{% for i in (1..17) %}
  <img src="/images/{{ i }}.jpg">
{% endfor %}
</div>
