---
layout: page
title: Events
permalink: /events/
---
<h3 id="latest_events"> <i>Latest Events</i> </h3>

{% assign sorted_events = site.Latest_events | sort:"chapter" %}
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
  <p>{{ entry.content | slice: 200, 520 }} <a class="news-link" href="/events/I/ch1/">Read more <img src="../../assets/icons/external-link-icon.svg" /></a></p>
  
{% endfor %}

<h3 id="regular_events"> <i>Regular Events</i> </h3>

{% assign sorted_events = site.Regular_events | sort:"chapter" %}
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
  <p>{{ entry.content | markdownify }}</p>
{% endfor %}

<h3 id="stakeholder_events"> <i>Stakeholder Engagement Events</i></h3>

{% assign sorted_events = site.Stakeholder_engagement_events | sort:"chapter" %}
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
  <p>{{ entry.content | markdownify }}</p>
{% endfor %}

<h3 id="more_events"> <i>More Events</i></h3>

{% assign sorted_events = site.More_events | sort:"chapter" %}
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
  <p>{{ entry.content | markdownify }}</p>
{% endfor %}

[mubas-organization]: http://www.mubas.ac.mw
