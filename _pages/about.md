---
layout: page
title: About
permalink: /about/
---

<div class="bios">
{% for contrib in site.data.bio %}
	<div class="bio">
		{% if contrib.img %}
		<div class="top">
			<div class="short">
			<h2>{{ contrib.name }}</h2>
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
</div>

<hr>
<h2>Other Public Interest Tech Fellows</h2>
<div class="fellows">
{% for contrib in site.data._config.fellows %}
	<div class="bio">
		<div class="top">
			<div class="short">
			<h2>{{ contrib.name }}</h2>
			{% for link in contrib.links %}
				<a href="{{link.link}}">{{link.title}}</a><br/>
			{% endfor %}		
			<ul>
			{% for mini in contrib.mini %}
				<li>{{mini.item}}</li>
			{% endfor %}			
			</ul>	
			</div>
			{% if contrib.img %}
				<img src="http://newamericapit.github.io/_config/images/{{ contrib.img }}">
			{% else %}
				<img src="http://newamericapit.github.io/_config/images/nophoto.png">
			{% endif %}
		</div>
	</div>
{% endfor %}
</div>
<a class="github-button" href="https://github.com/readywater/pitblog" data-style="mega" data-count-href="/readywater/pitblog" data-count-api="/repos/readywater/pitblog#stargazers_count" data-count-aria-label="# readywater on GitHub" aria-label="Star readywater/pitblog on GitHub">Star</a>
<script async defer src="https://buttons.github.io/buttons.js"></script>