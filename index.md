---
layout: default
permalink: /
title: 
---

<div class="page-lead" style="background-image:url(https://cfars.github.io/images/montage.png)">
  <div class="wrap page-lead-content">
	<h1>#LiDAR<span style="color:#4444ff">Stands</span>Alone</h1>
	<h2><span style="color:#4444ff">C</span>onsortium <span style="color:#4444ff">F</span>or the <span style="color:#4444ff">A</span>dvancement of <span style="color:#4444ff">R</span>emote <span style="color:#4444ff">S</span>ensing.</h2>
  </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
