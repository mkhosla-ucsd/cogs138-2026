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

- implement a method from a recent paper (not more than 10 years ago) on a new dataset, or
- formulate your own neuroscience question and design an analysis pipeline to answer it.

## Deliverables

| Date | Milestone |
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

You will turn in one PDF as a group into Gradescope by the due date for the proposal and one jupyter notebook as a group into datahub for the final component of the project. There are no late submissions accepted for the notebook submission, unless there is an issue outside of your control. If so, email your course instructor and all your teammates before the due date.
