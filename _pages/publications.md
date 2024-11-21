---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find a full list at my <a href="{{site.author.googlescholar}}">Google Scholar</a> profile.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
