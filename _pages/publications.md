---
layout: page
permalink: /publications/
title: publications
description: Please contact me for further information on any of these papers. Most of the full versions are available online and can be found via Google Scholar. I am in the process of adding relevant links here.
years: [2018,2017,2016,2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2003,2002]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
