---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

1. //{% if site.author.googlescholar %}
2. // <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
3. // {% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
