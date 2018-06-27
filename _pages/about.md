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
			{% if contrib.img %}
				<img src="http://newamericapit.github.io/_config/images/{{ contrib.img }}">
			{% else %}
				<img src="http://newamericapit.github.io/_config/images/nophoto.png">
			{% endif %}
			<div class="short">
			<h2>{{ contrib.name }}</h2>
			{% if contrib.alum %}
				<span class="alum">Alumni</span>
			{% endif %}		
			<ul>
			{% for mini in contrib.mini %}
				<li>{{mini.item}}</li>
			{% endfor %}			
			</ul>	
			</div>
		</div>
	</div>
{% endfor %}
</div>