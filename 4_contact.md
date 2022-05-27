---
layout: default
title: Contact
permalink: /contact/
---

Drop me a message :)

{% for item in site.data.social %}
## [{{ item.title }}]({{ item.link }})
{% endfor %}