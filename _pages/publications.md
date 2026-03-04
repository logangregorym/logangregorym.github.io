---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
description: "Research publications by Logan Moody on computer architecture security and performance, including side-channel attacks and microarchitectural optimizations."
---

My research sits at the intersection of **computer architecture security** and **microarchitectural performance**, with a focus on how aggressive front-end optimizations in modern processors interact with security boundaries. I study both how these optimizations create exploitable timing side channels, and how speculative techniques can be harnessed to improve processor efficiency.

{% if author.googlescholar %}
Also on <a href="{{ author.googlescholar }}">Google Scholar</a>.
{% endif %}

{% include base_path %}

<div class="pub-list">
{% for post in site.publications reversed %}
  {% include pub-single.html %}
{% endfor %}
</div>
