---
layout: default
permalink: /
title: "Home"
<!-- image:
  feature: MSP_Lakes.jpg -->
---
<div class="page-lead" style="background-image:url(https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/Lake_of_the_Isles_Skyline_%2815622093049%29.jpg/1200px-Lake_of_the_Isles_Skyline_%2815622093049%29.jpg)">
  <div class="wrap page-lead-content">
        <h1>Northern Widget</h1>
        <h2>Open source for the outdoors</h2>
        <h5>Made in Minnesota <br> Developing insturmentation and sensors for enviromental monitoring since 2013</h5>
<!--         <a href="https://mmistakes.github.io/skinny-bones-jekyll/getting-started/" class="btn-inverse">Start Using Skinny Bones</a> &nbsp; or &nbsp; <a href="https://github.com/mmistakes/skinny-bones-jekyll" class="btn-inverse">View on GitHub</a> -->
      </div><!-- /.page-lead-content -->
</div><!-- /.page-lead -->

<div id="page-wrapper">
      <!--[if lt IE 9]><div class="upgrade notice-warning"><strong>Your browser is quite old!</strong> Why not <a href="http://whatbrowser.org/">upgrade to a newer one</a> to better enjoy this site?</div><![endif]-->


<div id="main" role="main">
  <div class="wrap">
    <div class="page-title">
      <h1></h1>
      
    </div>
<div class="archive-wrap">
  <div class="page-content">
    <div class="tiles">

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
