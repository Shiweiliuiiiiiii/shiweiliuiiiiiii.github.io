---
layout: page
permalink: /blog/
title: Blog
description: Research stories and ideas on building more capable and efficient AI.
nav: true
nav_order: 4
pagination:
  enabled: false
---

{% assign research_posts = site.posts | where: "research_blog", true | sort: "date" | reverse %}

<ul class="post-list">
  {% for post in research_posts %}
    <li>
      <h2><a class="post-title" href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.description }}</p>
      <p class="post-meta">
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%B %d, %Y' }}</time>
        &middot; {{ post.content | strip_html | number_of_words | divided_by: 200 | plus: 1 }} min read
      </p>
      <p>From pruning convolutional networks to the Curse of Depth, attention residuals, and useful recurrent computation.</p>
      <p><a href="{{ post.url | relative_url }}">Read the article</a></p>
    </li>
  {% else %}
    <li><p>New research articles are coming soon.</p></li>
  {% endfor %}
</ul>
