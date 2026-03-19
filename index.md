---
title: Home
layout: default
nav_exclude: false
nav_order: 1
---

{% assign variables = site.data[site.data_folder].variables %}
{% assign course_calendar = site.data[site.data_folder].course_calendar %}
{% assign offset_week = 1 %}
{% assign first_date = course_calendar[0].date | date: '%s' %}
{% assign first_day = course_calendar[0].date | date: '%w' %}

{: .text-grey-dk-200 .lh-0 .pt-4 }
Neural Data Science
{: .text-grey-dk-300 .fw-300 .lh-0 }
## COGS 138 · UC San Diego · Prof. Meenakshi Khosla
{{ variables.quarter }}
{: .label .label-purple }
{{ variables.building }}
{: .label .label-purple }
{{ variables.timings }}
{: .label .label-purple }

## Welcome

Welcome to **COGS 138: Neural Data Science**. This site is the central hub for course logistics, schedules, deadlines, readings, and project information.

{: .note }
This Spring 2026 site is adapted from a previous offering of the course. The overall structure is ready to use, and the calendar has been updated for Spring 2026. Any links or staffing details marked TBD can be filled in as the quarter unfolds.

## Quick links

- [Getting Started]({{ site.baseurl }}/getting-started/)
- [Office Hours]({{ site.baseurl }}/office-hours/)
- [Syllabus]({{ site.baseurl }}/syllabus/)
- [Readings]({{ site.baseurl }}/readings/)
- [Assignments]({{ site.baseurl }}/assignments/)
- [Final Project]({{ site.baseurl }}/final-group-project/)

## Course Calendar

| Week | Date | Tag | Item |
|:-----|:-----|:----|:-----|
{% for row in course_calendar %}
  {% assign week_no = row.date | date: '%s' | minus: first_date | divided_by: 60 | divided_by: 60 | divided_by: 24 | plus: first_day | minus: 1 | divided_by: 7 | plus: offset_week %}
| Week {{ week_no }} | {{ row.date | date: "%a, %b %d" }} | {% if row.label %}`{{ row.label }}`{% endif %} | {{ row.title }} |
{% endfor %}
