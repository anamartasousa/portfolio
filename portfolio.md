---
layout: page
title: Portfolio
---
{% for portfolio in site.portfolio %}
<div class="portfolio">
<h2><a href="{{site.baseurl}}/portfolio/{{portfolio.slug}}">{{portfolio.title}}</a></h2>
{{portfolio.summary}}
</div>

{% endfor %}


{% for item in site.data.cvwork %}
{{ item.title }} {{ item.institution }} {{ item.description }} {{ item.time }}
{% endfor %}