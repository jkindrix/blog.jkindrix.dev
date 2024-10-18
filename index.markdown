---
layout: home
title: "Justin Kindrix's Blog"
description: "Insights, tutorials, and updates from Justin Kindrix."
---

# Welcome to My Blog

Hello, I'm Justin Kindrix. This is where I share insights, tutorials, and updates on various topics, ranging from software development to personal projects.

## Latest Posts

{% if site.posts.size > 0 %}
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
        <small>{{ post.date | date: "%B %d, %Y" }}</small>
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No posts yet. Stay tuned for upcoming content!</p>
{% endif %}

## About Me

Learn more about me and my work on the [About page](/about/).
