---
layout: default
permalink: /
title: 
---

<div class="page-lead" style="background-image:url(https://cfars.github.io/images/montage.png)">
  <div class="wrap page-lead-content">
	<h1>#LiDAR<span style="color:#aaaaaa">Stands</span>Alone</h1>
	<h2>Consortium for Advancement of Remote Sensing.</h2>
  </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
