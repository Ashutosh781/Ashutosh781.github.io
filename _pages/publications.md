---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my [Google Scholar profile]({{site.author.googlescholar}}).

Conference Papers
======

{% include base_path %}

{% for post in site.publications_conference reversed %}
  {% include archive-single.html %}
{% endfor %}

Workshop Papers
======

{% include base_path %}

{% for post in site.publications_workshop reversed %}
  {% include archive-single.html %}
{% endfor %}
