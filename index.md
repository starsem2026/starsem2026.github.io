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
<div class="home-two-col">

  <!-- Left column: Important dates -->
  <div class="left-col">
    <h3>📅 Important Dates</h3>

    {% capture dates_table %}
    {% include important_dates.md %}
    {% endcapture %}
    {{ dates_table | markdownify }}

    <div class="dates-link">
      <a href="/dates/">See all dates →</a>
    </div>
  </div>

  <!-- Right column: feature tiles -->
  <div class="right-col">
    {% include feature_row %}
  </div>

</div>  <!-- end home-two-col -->

<hr style="margin-top: 20px;">

<style>
.home-two-col {
  display: flex;
  gap: 24px;
  margin: 24px 0 32px;
  align-items: flex-start;
}

/* LEFT COLUMN */
.left-col {
  flex: 1;
  background: #fff;
  border: 1px solid #e5e5ea;
  border-radius: 12px;
  padding: 16px 18px;
  box-shadow: 0 1px 2px rgba(0,0,0,.04);
  max-width: 330px;
}

.left-col table {
  width: 100%;
  border-collapse: collapse;
}
.left-col th, .left-col td {
  padding: 6px 10px;
  white-space: nowrap;
}
.left-col tr:nth-child(even) td {
  background: rgba(0,0,0,.03);
}
.left-col h3 {
  text-align: center;
  margin-top: 0;
}
.dates-link {
  text-align: center;
  margin-top: 8px;
  font-size: .9rem;
}

/* RIGHT COLUMN */
.right-col {
  flex: 2;
}

/* MOBILE */
@media (max-width: 768px) {
  .home-two-col {
    flex-direction: column;
  }
  .left-col {
    max-width: 100%;
  }
}
</style>

