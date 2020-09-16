---
layout: archive
permalink: /
title: "Latest Posts"
---

<header id="masthead">
  <div class="inner-wrap">
    <a href="https://mmistakes.github.io/jekyll-theme-skinny-bones/" class="site-title">Skinny Bones</a>
    <nav role="navigation" class="menu top-menu">
        <ul class="menu-item">
	<li class="home"><a href="/">Skinny Bones</a></li>
	
    
    <li><a href="https://mmistakes.github.io/jekyll-theme-skinny-bones/getting-started/" >Getting Started</a></li>
  
    
    <li><a href="https://mmistakes.github.io/jekyll-theme-skinny-bones/articles/" >Sample Articles</a></li>
  
    
    <li><a href="https://mmistakes.github.io/jekyll-theme-skinny-bones/media/" >Media</a></li>
  
    
    <li><a href="https://mmistakes.github.io/jekyll-theme-skinny-bones/about/" >About</a></li>
  
</ul>
    </nav>
  </div><!-- /.inner-wrap -->
</header><!-- /.masthead -->

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
