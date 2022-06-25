---
layout: home
title: 'CS 121/ INF 141: Information Retrieval'
nav_exclude: true
permalink: index.html
seo:
  type: Course
  name: 'CS 121/ INF 141: Information Retrieval, Fall 2021'
---
# CS 121/ INF 141: Information Retrieval

{% assign instructors = site.staffers | where: 'role', 'course' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Catalogue description
An introduction to information retrieval including indexing, retrieval, classifying, and clustering text and multimedia documents.


{% if site.announcements.size != 0 %}
## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

{% endif %}