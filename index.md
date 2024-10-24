---
title: Skilling assets repository index
permalink: index.html
layout: home
---

# Asset repository index
Below you will find links to various assets grouped by asset type.

## Demos

{% assign demos = site.pages | where_exp: "page", "page.url contains '/demos'" %}
| Title | Description |
| --- | --- |
{% for demo in demos  %}{% if demo.metadata.title %}| {{ activity.metadata.title }} | [{{ activity.metadata.description }}]({{ site.metadata.link }}) |
{% endif %}{% endfor %}

## iEngage/gamification

## Whiteboarding
