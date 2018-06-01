---
layout: archive
title: Products
permalink: /products/
catgory: products
---

This is the base text for the Products heading 

<!-- <ul>
  	{% for post in site.categories.products %}
 	<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul> -->

<!-- Used for writing out all of the relevent posts in a list -->
<ul>
  	{% for post in site.categories.products %}
 	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>
