---
layout: post
title: Blog
permalink: /blog/
menu: true
---

Click [here](/blog/tags/) to view by tag

<div>
{% for post in site.posts %}
	<h2> {{ post.date | date: "%Y-%m-%d" }}: <a href="{{post.url}}">{{post.title}}</a></h2>
{% endfor %}
</div>
