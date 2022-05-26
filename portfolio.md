---
layout: default
title: Portfolio
---
{% for portfolio in site.portfolio %}
<div class="portfolio">
<h2><a href="{{site.baseurl}}/portfolio/{{portfolio.slug}}">{{portfolio.title}}</a></h2>
<p>{{portfolio.summary}}</p>
</div>

{% endfor %}