---
layout: page
title: interesting links
nav_order: 2
nav: true
permalink: /interesting-links/
---

# Useful Links

This page contains a collection of links that I frequently visit (not necessarily for research).

{% for link in site.interesting_links %}
- [{{ link.title }}]({{ link.url }})
{% endfor %}
