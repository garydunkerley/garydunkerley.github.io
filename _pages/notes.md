<!---
---
layout: archive
title: "Notes & Writing"
permalink: /notes/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
--->


---
layout: archive
title: "Notes & Writing"
permalink: /notes/
author_profile: true
---

{% if site.notemap_link == true %}

<p style="text-decoration:underline;"><a href="/notemap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.notes reversed %}
  {% include archive-single-note.html %}
{% endfor %}

