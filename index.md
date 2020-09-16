---
layout: default
permalink: /
title: 
---

<div class="page-lead" style="background-image:url(https://cfars.github.io/images/montage.png)">
  <div class="wrap page-lead-content">
	<h1>Skinny Bones</h1>
	<h2>Jump start your Jekyll site with something thin and light.</h2>
  </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
