---
layout: default
title: Final Project
has_children: false
nav_order: 8
permalink: /final-group-project/
---

{% assign course_calendar = site.data[site.data_folder].course_calendar %}

# Final Project

For the final project, students should identify a neuroscience question that can be addressed using available data and computational analysis.

A good starting structure is to choose one of the following:

- implement a method from a recent paper on a new dataset, or
- formulate your own neuroscience question and design an analysis pipeline to answer it.

## Deliverables

| Date | Milestone |
|:-----|:----------|
{% for row in course_calendar %}
  {% if row.label == 'PROJ' %}
| {{ row.date | date: "%a, %b %d" }} | {{ row.title }} |
  {% endif %}
{% endfor %}

## Expected final product

A strong final project should include:

- a clear research question,
- motivation and relevant background,
- a transparent computational workflow,
- figures that support the main conclusions,
- and a concise interpretation of the results.

{: .note }
This page is set up as a clean placeholder adapted from the prior course website. You can expand it with a proposal template, notebook guidelines, and presentation instructions whenever you are ready.
