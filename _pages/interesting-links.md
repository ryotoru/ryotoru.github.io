---
layout: page
title: Interesting Links
permalink: /interesting-links/
---

# Useful Links

This page contains a collection of links that I frequently reference for my research work.

{% for link in site.research_links %}
- [{{ link.title }}]({{ link.url }})
{% endfor %}
