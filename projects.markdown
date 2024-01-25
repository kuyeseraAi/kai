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

[OHDSI]:   [https://www.ohdsi.org]
[inspireweb]:   [https://inspiredata.network/about]
[c19catalog]:   [https://healthdataafrica.org/]
