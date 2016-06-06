---
layout: page
title: Blog
permalink: /blog/
image: /img/optimized/vertical_house.jpg
weight: 100
---

<ul class="post-list blog-post-list">
{% for post in site.categories.blog limit:3 %}
  <li>
    <a class="post-list-image blog-post-list-image" href="{{ post.url | prepend: site.baseurl }}" style="background-image:url('{{ post.image | prepend: site.baseurl }}')">
    </a>
    <h2 class="post-link">
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <p>{{ post.excerpt | remove: '<p>' | remove: '</p>' }}</p>
    <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">Read More >></a>
  </li>
{% endfor %}
</ul>