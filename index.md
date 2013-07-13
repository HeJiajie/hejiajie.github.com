---
layout: page
title: Latest Post
---
{% include JB/setup %}

<div class="blog-index">
{% assign post = site.posts.first %}
{% assign content = post.content %}
{% include jiajie/post_detail.html %}
</div>

