---
layout: archive
title: Software
permalink: /software/
catgory: software
---

This is the base text for the Products heading 

<!-- <ul>
  	{% for post in site.categories.products %}
 	<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul> -->

<!-- Used for writing out all of the relevent posts in a list -->
<ul>
  	{% for post in site.categories.software %}
 	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>