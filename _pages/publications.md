---
layout: archive
title: ""
permalink: /publications/
author_profile: true
header: 
  image: /publications_header2.jpg
---

![header2](/images/publications2.png)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
