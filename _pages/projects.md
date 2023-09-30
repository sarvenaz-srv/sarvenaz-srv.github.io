---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

You can find full details of my projects on [GitHub](https://github.com/sarvenaz-srv){:target="_blank"}!
{: .notice}

{% for post in site.projects reversed %}
  {% include projects.html %}
{% endfor %}
