---
layout: archive
permalink: /
title: "News"
---
![Burkholderia biofilm diversification](/images/burk-fm.gif)
<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
