---
layout: splash
title: "*SEM 2026"
excerpt: "The 15th Joint Conference on Lexical and Computational Semantics"
permalink: /
header:
  overlay_image: /assets/images/san_diego_skyline.jpg
  overlay_filter: 0.35
  actions:
    - label: "Call for Papers"
      url: /calls/
    - label: "Important Dates"
      url: /dates/

intro:
  - excerpt: >
      The 15th Joint Conference on Lexical and Computational Semantics (*SEM 2026)
      is organized and sponsored by SIGLEX (ACL), and will be colocated with
      [ACL 2026](https://acl2026.org). *SEM brings together researchers interested
      in the semantics of natural languages and its computational modeling.

feature_row:
  - title: "Author Guidelines"
    url: "/calls/"
    excerpt: "Topics, formatting, ethics, anonymity, and submission."
  - title: "Program"
    url: "/program/"
    excerpt: "Schedule, keynotes, and accepted papers."
  - title: "Venue & Travel"
    url: "/venue/"
    excerpt: "Location, hotels, visas, and local info."
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}




## Important Dates

{% capture dates_table %}
{% include important_dates.md %}
{% endcapture %}

<div class="dates-highlight">
  {{ dates_table | markdownify }}
</div>

<style>
.dates-highlight{
  background: #f7f7f9;
  border: 1px solid #e5e5ea;
  border-radius: 12px;
  padding: 16px 18px;
  margin: 24px 0 8px;
  box-shadow: 0 1px 2px rgba(0,0,0,.04);
}
.dates-highlight table{
  width: 100%;
  margin: 0;
}
.dates-highlight th,
.dates-highlight td{
  padding: 8px 10px;
}
.dates-highlight tr:nth-child(even) td{
  background: rgba(0,0,0,.03);
}
</style>



