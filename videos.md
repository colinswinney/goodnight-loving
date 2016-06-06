---
layout: page
title: Videos
permalink: /videos/
image: /img/optimized/gnl_zach_red_blur.jpg
weight: 3
---

<ul class="post-list video-post-list">
{% for post in site.posts reversed %}
{% if post.categories contains 'videos' %}
  <li>
    <a class="post-list-image" href="{{ post.url | prepend: site.baseurl }}" style="background-image:url('{{ post.image | prepend: site.baseurl }}')">
    </a>
    <h2>
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h2>
  </li>
{% endif %}
{% endfor %}
</ul>