---
layout: page
title: Quills of Springdew Sessions
permalink: /Quills/sessions/
---

This page contains a list of sessions for the Quills of Springdew campaign.

{% assign sessions = site.posts | where_exp:"item", "item.tags contains 'quills' and item.tags contains 'session'" %}

{% for post in sessions %}
    - <a href="{{ site.quillsurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
