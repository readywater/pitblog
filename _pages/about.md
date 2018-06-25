---
layout: page
title: About
permalink: /about/
---


{% for contrib in site.data.bio %}
	<div class="bio">
		{% if contrib.img %}
		<div class="top">
			<div class="short">
			<h3>{{ contrib.name }}</h3>
			{% for link in contrib.links %}
				<a href="{{link.link}}">{{link.title}}</a><br/>
			{% endfor %}		
			<ul>
			{% for mini in contrib.mini %}
				<li>{{mini.item}}</li>
			{% endfor %}			
			</ul>	
			</div>
			<img src="{{ contrib.img }}">
		</div>
		{% endif %}
		<div class="bio-text">{{ contrib.bio}}</div>
	</div>
{% endfor %}

<a class="github-button" href="https://github.com/readywater/pitblog" data-style="mega" data-count-href="/readywater/pitblog" data-count-api="/repos/readywater/pitblog#stargazers_count" data-count-aria-label="# readywater on GitHub" aria-label="Star readywater/pitblog on GitHub">Star</a>
<script async defer src="https://buttons.github.io/buttons.js"></script>