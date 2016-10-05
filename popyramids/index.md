---
layout: archive
title: "Popyramids Gallery"
date: 2016-10-04T00:00:00-00:00
modified:
excerpt:
tags: []
image:
  feature:
  teaser:
---

The popyramids database was the first chichinabo project. It stores population data by sex and age groups, associated to a geographical area.

This gallery shows different apps that explore the popyramids database. You can check the current data availability in the [project's wiki](project's wiki).

<div class="tiles">
{% for post in site.categories.popyramids %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
