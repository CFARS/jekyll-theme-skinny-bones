---
layout: default
permalink: /
title: 
---

<div class="page-lead" style="background-image:url(https://cfars.github.io/images/montage.png)">
  <div class="wrap page-lead-content">
	<h1>#LiDAR<span style="color:#aaaaff">Stands</span>Alone</h1>
	<h2><span style="color:#aaaaff">C</span>onsortium <span style="color:#aaaaff">F</span>or the <span style="color:#aaaaff">A</span>dvancement of <span style="color:#aaaaff">R</span>emote <span style="color:#aaaaff">S</span>ensing.</h2>
  </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
