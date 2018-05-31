---
layout: article
permalink: /
title: "Latest Posts"
---
This is a test to see if Jekyll Local Build is functional...
To see how long updates take 
<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
