---
layout: default
title: "Posts"
permalink: /posts/
---

{% include nav.html nav=site.data.menu %}

## Posts ##
<ul>
{% for post in site.posts %}
<li> | <a href="{{post.url}}">{{post.title}}</a> ({{post.date | date: '%B %d, %Y'}}) | </li>
{% endfor %}
</ul> 