---
layout: archive
title: Loggers
permalink: /products/loggers/
catgory: loggers
---

This is the base text for the Logger sub page

<!-- <ul>
  	{% for post in site.categories.products %}
 	<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul> -->

<!-- Used for writing out all of the relevent posts in a list -->
<ul>
  	{% for post in site.categories.loggers %}
 	<li><h3><a href="{{ post.url }}">{{ post.title }}</a></h3></li>
 	<img src="{{ site.baseurl }}/images/{{ post.image.teaser }}" style="width:150px;height:150px;" />
	{% endfor %}
</ul>