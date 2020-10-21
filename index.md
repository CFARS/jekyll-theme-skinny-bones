---
layout: default
permalink: /
title: 
---

<div class="page-lead" style="background-image:url(https://cfars.github.io/images/montage.png)">
  <div class="wrap page-lead-content">
	<h1>CFARS</h1>
	<h2>CONSORTIUM FOR ADVANCEMENT OF REMOTE SENSING.</h2>
  </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts.categories.meetings %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
