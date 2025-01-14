---
title:  "Opioids in West Hawaii series"
layout: archive
publication: "West Hawaii Today"
date: 2018-07-16 00:00:00 +0000
entries_layout: grid
header:
    teaser: "assets/images/opioids_cover.jpg"
    caption: "A vial of naloxone sits next to educational material about how to respond to an overdose. (Cameron Miculka/West Hawaii Today)"
date:   2018-07-16 00:00:00 +0000
collection: opioids
sort_field: order
sort_order: reverse
---
*In July 2018, West Hawaii Today published my four-part series I produced exploring the local opioid crisis, including interviews with local experts in public health and addiction along with medical professionals about the state of opioid use and misuse in Hawaii County and what measures are being taken and need to be taken to help those with or susceptible to opioid use disorder.*

{% assign posts = site.opioids %}

{% assign entries_layout = page.entries_layout | default: 'list' %}
<!-- <div class="entries-{{ entries_layout }}">
  {% include documents-collection.html entries=posts type=entries_layout %}
</div> -->

<div id = 'opioids-grid'>
  {% include documents-collection.html entries=posts type=entries_layout %}
</div>