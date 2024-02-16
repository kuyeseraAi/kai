---
layout: page
title: Events
permalink: /events/
---

<h3 id="current_events"> <i>Regular Events</i> </h3>

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

<h3 id="current_events"> <i>More Events</i></h3>

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

{% comment %}

**KAI** Lab organises the following events:
1. Annual Machine Learning Symposium IndabaX Malawi: **last event Beg. of May 2023**
2. Data Analytics competitions: **last run April 2022**
3. Trainings: Online Training with Inspire Network: Data Harmonisation
4. Machine Learning Meet-ups: **started 1st April 2023**

<br />
**PAST EVENTS**

* **INSPIRE PEACH Dissemination Workshop: 26 - 27 June 2023, Blantyre**
<br />The Lab took part in the INSPIRE PEACH Dissemination Workshop held on 26th and 27th June 2023 in Blantyre, Malawi. The lead, Dr Amelia Taylor, gave a presentation on <a class="page-link" href="https://docs.google.com/presentation/d/1H_-XLWP0J3WfhdAC57n5nINHroAkClrh/edit?usp=drive_link&ouid=103243696572721185208&rtpof=true&sd=true" target="_blank">Lessons and Applications from utilising OMOP to Malawi Data.</a>

* **The Pan African Big Data, Analytics and AI 3rd Annual Conference: 27th - 28th April, 2023, Lilongwe**
<br />The Lab also took part in the Pan African Big Data, Analytics and AI 3rd Annual Conference held on 27th and 28th April, 2023 in Lilongwe, Malawi. The lead, Dr Amelia Taylor, gave a presentation on <a class="page-link" href="https://docs.google.com/presentation/d/1HlhHs_QWGOmVDFpzyzCaEoadcYN78Von/edit?usp=share_link&ouid=103243696572721185208&rtpof=true&sd=true" target="_blank">AI for Organisations in Malawi.</a> Moses Gwaza (developer) also gave a presentation on <a class="page-link" href="https://docs.google.com/presentation/d/1jlZMlvXv9h065tyyQioN7FBik0dkq4Xx/edit?usp=share_link&ouid=103243696572721185208&rtpof=true&sd=true" target="_blank">Using OHDSI for health informatics in Malawi.</a>

{% endcomment %}

[mubas-organization]: http://www.mubas.ac.mw
