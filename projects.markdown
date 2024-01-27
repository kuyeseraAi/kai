---
layout: page
title: Projects
permalink: /projects
nav: true
---

The Kuyesera AI Lab has several projects ongoing. We list them below and provide links to individual project pages.

{% assign orderedlist = site.Projects | sort:"order" %}
{% for entry in orderedlist %}
  <p>
    <a href="{{site.baseurl}}{{entry.url}}">
      {{ entry.title }}
    </a>
  </p>
{% endfor %}

**Our partners are**:

1. The Public Health Institute of Malawi (PHIM)
2. Blantyre and Lilongwe DHOs
3. African Population and Health Research Center
4. London School of Hygene and Tropical Medicine
5. EGPAF Malawi

**We are grateful to our funders:** Wellcome Trust, IDRC, SIDA, Bill & Melinda Gates foundation. 


[OHDSI]:   [https://www.ohdsi.org]
[inspireweb]:   [https://inspiredata.network/about]
[c19catalog]:   [https://healthdataafrica.org/]
