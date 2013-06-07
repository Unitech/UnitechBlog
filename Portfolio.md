---
layout: page
title: Unitech.io App Portfolio 
menu_title : Portfolio
header: 
//group: navigation
---
{% include JB/setup %}

<h1>Unitech assemblage</h1>

{% for post in site.categories.Apps %}
<section>
	<div class="row">
		<div class="span2">		
			<img src="/img/{{post.preview_img}}">
		</div>
		<div class="span8">
			{{post.content}}
		</div>
	</div>
</section>
{% endfor %}

