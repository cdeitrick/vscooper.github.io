---
layout: archive
permalink: /
title: "News"
---
![Burkholderia biofilm diversification](https://github.com/vscooper/vscooper.github.io/blob/master/images/burk-fm.gif)
<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
