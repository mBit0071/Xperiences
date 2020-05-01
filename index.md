---
title: Xperiences
layout: default
---

# {{ page.title }}

This is my space where I can jot down my thoughts, dreams, experiences. 

### Landing page links

{% for ps in site.categories %}
1. [{{ps | first | strip_html}}]({{site.baseurl}}{{ps | first | strip_html}})
{% endfor %}


