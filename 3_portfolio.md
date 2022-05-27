---
layout: default
title: Portfolio
permalink: /portfolio/
---

{% for project in site.data.projects %}
## [{{ project.title }}]({{site.baseurl}}/portfolio/{{project.slug}})
![project.alt]({{site.baseurl}}/{{ project.img }})
### {{ project.type }}
{{ project.description }}
#### {{ project.nature }}
##### {{ project.year }}

{% endfor %}