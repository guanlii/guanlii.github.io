---
title: Publications
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research


{% include section.html %}


## All

{% include search-box.html %}

{% include search-info.html %}

{%
  include list.html
  data="citations"
  component="citation"
  filter="date.between?('2015', '2030')"
  style="rich"
%}