---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

{% include_relative includes/bio.md %}
  
{% capture news_content %}
{% include_relative includes/news.md %}
{% endcapture %}

<div class="news-scroll">
  {{ news_content | markdownify }}
</div>

{% include_relative includes/publications.md %}

{% include_relative includes/services.md %}

{% include_relative includes/awards.md %}

<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=180&t=n&d=vgHAM2_bgXRzfvGbngV2UyR8zpDwmIGrUzOTC-UiWVI&co=36a1d2&cmo=ff0000'></script>

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=f4f4f4&w=300&t=n&d=v8UxswgHWuwHnWQprnMhxroGwaIwImX60ACfv3hW7sI&co=86b7c1&cmo=6982ff&cmn=ff69a0&ct=020000'></script>

