---
layout: default
title: Assignments
has_children: false
nav_order: 6
permalink: /assignments/
---

{% assign course_calendar = site.data[site.data_folder].course_calendar %}

# Assignments

Assignments are intended to reinforce the concepts covered in lecture and give you hands-on experience with neural data science tools and workflows.

## Assignment deadlines

| Date | Item |
|:-----|:-----|
{% for row in course_calendar %}
  {% if row.label == 'ASSG' %}
| {{ row.date | date: "%a, %b %d" }} | {{ row.title }} |
  {% endif %}
{% endfor %}

## Quizzes and exam

| Date | Item |
|:-----|:-----|
{% for row in course_calendar %}
  {% if row.label == 'QUIZ' or row.label == 'EXAM' %}
| {{ row.date | date: "%a, %b %d" }} | {{ row.title }} |
  {% endif %}
{% endfor %}

{: .note }
This page is pulling its deadlines directly from `_data/sp26/course_calendar.csv`, so you only need to edit the CSV to update both the home page calendar and this page.
