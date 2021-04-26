---
layout: page
permalink: /publications/
title: publications
description: Sorted by year. This list is created using jekyll scholar. For an official publication list, please refer to my <a href="http://lattes.cnpq.br/5862618116527136">Lattes CV</a>.
years: [2021, 2020, 2019, 2018, 2017, 2016, 2015]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography --query @*[year={{y}}]* %}
{% endfor %}
