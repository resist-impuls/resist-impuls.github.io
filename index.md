---
layout: archive
permalink: /
title: "Welcome to the RESIST website!"
---

![Sea ice](/images/seaice.png)

RESIST (Recent Arctic and Antarctic sea ice lows: same causes, same impacts?) is funded by the Belgian Science Policy Office ([BELSPO](https://www.belspo.be/belspo/index_en.stm)). Its aim is to document, qualitatively and quantitatively, the cause-effect relationships between summer sea ice lows in both polar regions and their potential interacting agents (drivers and impacts).

![BELSPO Logo](/images/BELSPO_logo.jpg")

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
