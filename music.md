---
layout: page
title: Music
permalink: /music/
image: /img/optimized/vertical-house-crowd.jpg
weight: 2
---

<ul class="post-list music-post-list">
{% for post in site.posts reversed %}
{% if post.categories contains 'music' %}
	<li>
    <span class="post-meta">{{ post.date | date: "%b %Y" }}</span>
    <a class="post-list-image" href="{{ post.url | prepend: site.baseurl }}" style="background-image:url('{{ post.image | prepend: site.baseurl }}')">
    </a>
    <span class="post-meta">{{ post.format }}</span>
    <h2 class="post-link">
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
    
    <p>{{ post.excerpt | remove: '<p>' | remove: '</p>' }}</p>
  </li>
{% endif %}
{% endfor %}
</ul>