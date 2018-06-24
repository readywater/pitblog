---
layout: page
title: About
permalink: /about/
---

<div class="bio">
	{% for contrib in site.data.bio %}
		{% if contrib.img %}
			<img src="{{ contrib.img }}">
		{% endif %}
		<div class="name">{{ contrib.name }}</div>
		<div class="bio">{{ contrib.bio}}</div>
		{% for link in contrib.links %}
			<a href="{{link.link}}">{{link.title}}</a><br/>
		{% endfor %}			
	{% endfor %}
</div>

<a class="github-button" href="https://github.com/readywater/pitblog" data-style="mega" data-count-href="/readywater/pitblog" data-count-api="/repos/readywater/pitblog#stargazers_count" data-count-aria-label="# readywater on GitHub" aria-label="Star readywater/pitblog on GitHub">Star</a>
<script async defer src="https://buttons.github.io/buttons.js"></script>