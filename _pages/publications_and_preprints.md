---
layout: archive
title: "Publications and Preprints"
permalink: /publications_and_preprints/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications_and_preprints reversed %}
  {% include archive-single.html %}
{% endfor %}
