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

<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=vgHAM2_bgXRzfvGbngV2UyR8zpDwmIGrUzOTC-UiWVI&cl=ffffff&w=a"></script>
