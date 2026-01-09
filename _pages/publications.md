---
layout: page
permalink: /publications/
title: Publications
description: List of my principal publications, conferences talks and theses.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2> Journal Articles </h2>

{% bibliography -q @article %}
{% bibliography -q @articlesec %}

<h2> Conferences and proceedings </h2>

{% bibliography -q @inproceedings %}

<h2> PhD Thesis </h2>

{% bibliography -q @phdthesis %}

<h2> Master Theses </h2>

{% bibliography -q @mastersthesis %}

</div>
