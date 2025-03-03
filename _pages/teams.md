---
title: "Teams"
layout: gridlay
excerpt: "Teams"
permalink: /teams/
---
<h1 style="text-align: center">Teams</h1>

<p style="text-align: center"><i>“Alone we can do so little; together we can do so much.”</i></p>
<div class="wrapper">
	<div class="divider div-transparent div-dot"></div>
{% comment %}############################################################################################################{% endcomment %}
<h2 style="text-align: center">Team Heads</h2>
{%for member in site.data.teams.Heads %}
<div class="grid__team">
<div class="grid__box" style="text-align: center">
  <img src="{{member.photo}}" width="50%" />
  <h3 width="50%">{{ member.name }}</h3>
  <i>{{ member.info }}</i> <br>
  <a href="{{ member.researchgate }}"><i class="fab fa-fw fa-researchgate" aria-hidden="true"></i></a>
  <a href="{{ member.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i></a>
  <a href="{{ member.linkedin }}"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i></a>
</div>
</div>
{% endfor %}<br>
<p style="text-align: center"> 2025 </p>

<div class="wrapper">
	<div class="divider div-transparent div-dot"></div>
{% comment %}############################################################################################################{% endcomment %}

