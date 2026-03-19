---
layout: default
title: Getting Started
has_children: false
nav_order: 2
permalink: /getting-started/
---

{% assign variables = site.data[site.data_folder].variables %}

# Getting Started

1. Check **Canvas** for announcements, logistics, and posted materials.
2. Check this site regularly for the course calendar, assignment deadlines, and project milestones.
3. Introduce yourself in class and keep an eye out for any course communication tools that will be activated for the quarter.
4. Stop by office hours or talk to us before/after class if you have questions about background, pacing, or project ideas.

{% if variables.canvas_link %}
- Canvas: [{{ variables.canvas_link }}]({{ variables.canvas_link }})
{% endif %}
{% if variables.gradescope_link %}
- Gradescope: [{{ variables.gradescope_link }}]({{ variables.gradescope_link }})
{% endif %}
{% if variables.piazza_link %}
- Piazza: [{{ variables.piazza_link }}]({{ variables.piazza_link }})
{% endif %}
{% if variables.pre_course_survey %}
- Pre-course survey: [{{ variables.pre_course_survey }}]({{ variables.pre_course_survey }})
{% endif %}

{: .note }
The page is set up so you can drop in the live Canvas / Gradescope / Piazza links later by editing `_data/sp26/variables.yml`.
