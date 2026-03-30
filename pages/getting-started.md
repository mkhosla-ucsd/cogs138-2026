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
5. Make sure you attend the discussion sections during week 2; we will be forming project groups and you'll want to meet your group mates
6. Fill out the **[pre-course survey]({{ variables.pre_course_survey }})** so we can start to get to know you better. And, stop by one of the office hours or come up to the front of the class before or after to say hi and introduce yourself! I'd love to meet and get to know you.
7. Join the class **Piazza**:
   - Use Piazza to ask questions and get help from your fellow students, TAs, IAs, and myself
   - Piazza link:  **[{{ variables.piazza_link }}]({{ variables.piazza_link }})**
   - Can also be accessed directly from the module on Canvas

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

