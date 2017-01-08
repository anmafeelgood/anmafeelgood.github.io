---
layout: home
permalink: /
image:
  feature: featured-home.jpg
title: "Latest Posts"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
