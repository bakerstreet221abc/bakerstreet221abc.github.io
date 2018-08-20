---
layout: page
title: About
description: Some description.
permalink: /about/
---


## 网站简介

Hi~这里是由推理迷Ellery和Sholmes发起的`The Mystery Project`，介绍关于推理的一切~欢迎广大推理迷一起来参与建设~

## Contributors

{% for author_id in site.data.authors.author_list %}
{% assign author = site.data.authors[author_id] %}
### {{ author.name }} 
<a herf='#{{author_id}}'></a>
<img itemprop="image" class="img-rounded" src="{{ author.avatar }}" alt="{{ author.name }}" width="200">
{{ author.long_tag }}
{% endfor %}

