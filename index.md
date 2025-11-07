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

{% capture dates_table %}
{% include important_dates.md %}
{% endcapture %}

<div class="home-dates">
  <h3>📅 Important Dates</h3>
  {{ dates_table | markdownify }}
  <div class="dates-link"><a href="/dates/">See all dates →</a></div>
</div>

{% include feature_row %}

<style>
.home-dates{
  display: inline-block;          /* shrink to table width */
  background: #fff;               /* no full-width highlight */
  border: 1px solid #e5e5ea;
  border-radius: 12px;
  padding: 12px 14px;
  margin: 12px auto 24px;         /* center under the excerpt */
  box-shadow: 0 1px 2px rgba(0,0,0,.04);
}
.home-dates h3{
  margin: 0 0 8px;
  text-align: center;
}
.home-dates table{
  width: auto;                    /* no 100% stretch */
  margin: 0 auto;                 /* center the table */
  border-collapse: collapse;
}
.home-dates th,
.home-dates td{
  padding: 6px 10px;
  white-space: nowrap;            /* keeps cells tidy */
}
.home-dates tr:nth-child(even) td{
  background: rgba(0,0,0,.03);
}
.home-dates .dates-link{
  text-align: center;
  font-size: .9rem;
  margin-top: 6px;
}
@media (max-width: 480px){
  .home-dates{ width: 100%; }     /* full width on small screens */
  .home-dates table{ width: 100%; }
}
</style>



