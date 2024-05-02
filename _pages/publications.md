---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<h2 style="font-size:24px;">Working Papers</h2>
<div class="publications">
{% bibliography --query @*[keywords=workingpaper] %}
</div>

<h2 style="font-size:24px;">Research in Progress</h2>
<div class="publications">
{% bibliography --query @*[keywords=researchinprogress] %}
</div>

<h2 style="font-size:24px;">Journal Articles</h2>
<div class="publications">
{% bibliography --query @*[keywords=journalarticle] %}
</div>

<h2 style="font-size:24px;">Book Chapters</h2>
<div class="publications">
{% bibliography --query @*[keywords=bookchapter] %}
</div>
