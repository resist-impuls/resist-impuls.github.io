---
layout: archive
permalink: /
title: "Welcome to the RESIST website!"
---

<div> RESIST (Recent Arctic and Antarctic sea ice lows: same causes, same impacts?) is funded by the Belgian Science Policy Office (BELSPO). Its aim is to document, qualitatively and quantitatively, the cause-effect relationships between summer sea ice lows in both polar regions and their potential interacting agents (drivers and impacts).
</div>



<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
