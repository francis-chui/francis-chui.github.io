---
layout: default
title: Partners
---
## Collaborators
{% for collaborator in site.collaborators %}
  {% include card.html content=collaborator.content logo_url=collaborator.logo_url title=collaborator.name %}
{% endfor %}

## Supported by funding from
{% for supporter in site.funding %}
{% include card.html content=supporter.content logo_url=supporter.logo_url title=supporter.name %}
{% endfor %}
