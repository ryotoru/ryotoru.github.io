---
layout: page
title: Interesting Links
nav_order: 2
nav: true
permalink: /interesting-links/
---

# Useful Links

This page contains a collection of links that I frequently reference for my research work.

{% for link in site.interesting_links %}
- [{{ link.title }}]({{ link.url }})
{% endfor %}
