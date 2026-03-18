---
layout: default
title: Research
permalink: /research/
---

# Research

Things I'm actively investigating. Each topic collects everything I've found so far — questions asked, sources read, and what I've pieced together.

{% assign topics = site.research | group_by: "topic" | sort: "name" %}
{% for group in topics %}
## {{ group.name }}

{% for entry in group.items reversed %}
### {{ entry.title }}

*{{ entry.date | date: "%B %d, %Y" }}*

{{ entry.content }}

{% if entry.sources %}
**Sources:** {{ entry.sources }}
{% endif %}

---

{% endfor %}
{% endfor %}

{% if site.research.size == 0 %}
*No research published yet. Check back soon.*
{% endif %}
