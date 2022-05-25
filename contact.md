---
layout: page
title: Contact
permalink: /contact/
---

If you want to drop me a message, get in touch through any of the following:

{% for item in site.data.social %}
{{ item.title }} {{ item.handle }} {{ item.link }}
{% endfor %}