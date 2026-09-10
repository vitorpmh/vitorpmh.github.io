---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
tabs: true
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

{% tabs pubs %}

{% tab pubs Top-tier conferences and works %}

<div class="publications">
{% bibliography --group_by none --query @*[tier=top]* %}
</div>
{% endtab %}

{% tab pubs Others %}

<div class="publications">
{% bibliography --group_by none --query @*[tier=other]* %}
</div>
{% endtab %}

{% endtabs %}
