---
layout: page
title: Essays
description: Short essays by Joe Norton. Topics range from startups, programming, to the future of humanity.
h1: Food for thought
permalink: /
---
Here are some of my short essays:
---------------------------------

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}

More to come soon!
