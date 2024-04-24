---
layout: page
title: Events
permalink: /events/
---
<h3 id="regular_events"> <i>Upcoming Events</i> </h3>

{% assign sorted_events = site.Upcoming_events | sort:"chapter" %}
{% for entry in sorted_events %}
  <h4>
    <a href="{{site.baseurl}}{{entry.url}}">
      {{ entry.title }}
    </a>
  </h4>
  <p style="text-align:left;"> 
  <a class="" href="{{site.baseurl}}{{page.url}}#top">
  </a>
  </p>
  <p>{{ entry.highlights | markdownify }}</p>
{% endfor %}

<h3 id="regular_events"> <i>Past Events</i> </h3>

{% assign sorted_events = site.Past_events | sort:"chapter" %}
{% for entry in sorted_events %}
  <h4>
    <a href="{{site.baseurl}}{{entry.url}}">
      {{ entry.title }}
    </a>
  </h4>
  <p style="text-align:left;"> 
  <a class="" href="{{site.baseurl}}{{page.url}}#top">
  </a>
  </p>
  <p>{{ entry.highlights | markdownify }}</p>
{% endfor %}
