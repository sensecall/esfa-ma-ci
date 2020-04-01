---
layout: product
title: "Apprenticeships service: Continuous improvement design history"
description: "A place to view the various projects worked on by the Apprenticeships service Continuous improvement team."
breadcrumbs: false
eleventyExcludeFromCollections: true
---

<div class="govuk-grid-row">
{% for item in collections["product"] | sort("data.order") %}
{% if loop.index == 1 %}
<div class="govuk-grid-column-full govuk-!-margin-top-3">
<h2 class="govuk-heading-l">Manage apprenticeships</h2>
</div>
{% elseif loop.index == 4 %}
<div class="govuk-grid-column-full govuk-!-margin-top-3">
<h2 class="govuk-heading-l">Support</h2>
</div>
{% endif %}
<section class="govuk-grid-column-one-half govuk-!-margin-bottom-6">
<h3 class="govuk-heading-m govuk-!-margin-bottom-1">
<a href="{{ item.url }}">{{ item.data.title }}</a>
</h3>
<p class="govuk-body">{{ item.data.description }}</p>
</section>
{% endfor %}
</div>