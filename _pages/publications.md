---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

## Working Papers
<div class="publications">
{% bibliography --query @*[keyword=workingpaper] %}
</div>

## Research in Progress
<div class="publications">
{% bibliography --query @*[keyword=researchinprogress] %}
</div>

## Journal Articles
<div class="publications">
{% bibliography --query @*[keyword=journalarticle] %}
</div>

## Book Chapters
<div class="publications">
{% bibliography --query @*[keyword=bookchapter] %}
</div>
