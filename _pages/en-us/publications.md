---
page_id: publications
layout: page
permalink: /publications/
title: publications
navigation_title_key: publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

{% bibliography %}

<section aria-labelledby="theses">
<h2 id="theses">{{ site.data[site.active_lang].strings.bibliography.theses }}</h2>

{% bibliography --file theses --group_by none %}

</section>

</div>
