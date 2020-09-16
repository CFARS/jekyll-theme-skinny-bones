---
layout: archive
permalink: /
title: 
---

   <div class="page-lead" style="background-image:url(https://cfars.github.io/images/montage.png)">
      <div class="wrap page-lead-content">
        <h1>Skinny Bones</h1>
        <h2>Jump start your Jekyll site with something thin and light.</h2>
        <a href="https://mmistakes.github.io/jekyll-theme-skinny-bones/getting-started/" class="btn-inverse">Start Using Skinny Bones</a> &nbsp; or &nbsp; <a href="https://github.com/mmistakes/jekyll-theme-skinny-bones" class="btn-inverse">View on GitHub</a>
      </div><!-- /.page-lead-content -->
    </div><!-- /.page-lead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
