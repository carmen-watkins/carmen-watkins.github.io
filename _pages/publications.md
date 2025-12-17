---
title: "Carmen Watkins - Publications"
layout: gridlay
excerpt: "Carmen Watkins -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

Access all publications on [Google Scholar](https://scholar.google.com/citations?user=K_gzsJoAAAAJ&hl=en), [Research Gate](https://www.researchgate.net/profile/Carmen-Watkins-2), or contact me for a copy. 


{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
