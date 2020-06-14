---
layout: default
permalink: /
---

{% if site.google_analytics and jekyll.environment == 'production' %}
{% include analytics.html %}
{% endif %}

{% include landing.html %}