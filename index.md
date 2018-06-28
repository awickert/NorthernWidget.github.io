---
layout: default
permalink: /
title: "Home"
---

<meta name="viewport" content="width=device-width, initial-scale=1.0">
{% if screen.width < screen.height %}
<img src="../images/NWseal_500px.png" alt="Northern Widget seal" style="width:300px" align="left">
{% else %}
<div class="page-lead" style="background-image:url('../images/bannerAW.jpg')">
  <div class="wrap page-lead-content">
        <img src="../images/NWseal_500px.png" alt="Northern Widget seal" style="width:300px" align="left">
  </div>
</div>
 {% endif %}
<div id="page-wrapper">
<!--       [if lt IE 9]><div class="upgrade notice-warning"><strong>Your browser is quite old!</strong> Why not <a href="http://whatbrowser.org/">upgrade to a newer one</a> to better enjoy this site?</div><![endif] -->


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
