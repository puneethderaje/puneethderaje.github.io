---
layout: default
title: Publications
---

{% for pub in site.data.publications %}
## {{ pub.title }}

{{ pub.authors }}

{{ pub.venue }}, {{ pub.year }}

{% if pub.biorxiv %}[bioRxiv]({{ pub.biorxiv }}){% endif %}
{% if pub.journal %}[Published Version]({{ pub.journal }}){% endif %}
{% if pub.slides %}[Slides]({{ pub.slides }}){% endif %}

{% endfor %}

