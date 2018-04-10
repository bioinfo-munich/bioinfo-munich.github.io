---
layout: default
title: "Posts"
permalink: /posts/
---

{% include nav.html nav=site.data.menu %}

## Posts ##
| {% for post in site.posts %}<a href="{{post.url}}">{{post.title}}</a> ({{post.date | date: '%B %d, %Y'}}) |{% endfor %}
