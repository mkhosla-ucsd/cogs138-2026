---
layout: default
title: Office Hours
has_children: false
nav_order: 4
permalink: /office-hours/
---

{% assign variables = site.data[site.data_folder].variables %}

## Contact Info

**Instructor**

- {{ variables.instructor.name }}{% if variables.instructor.email %} — [{{ variables.instructor.email }}](mailto:{{ variables.instructor.email }}){% endif %}

**Teaching Assistants (TAs)**

{% for ta in variables.teaching_assistants %}
- {{ ta.name }}{% if ta.email %} — [{{ ta.email }}](mailto:{{ ta.email }}){% endif %}
{% endfor %}

**Instructional Assistants (IAs)**

{% for ia in variables.instructional_assistants %}
- {{ ia.name }}{% if ia.email %} — [{{ ia.email }}](mailto:{{ ia.email }}){% endif %}
{% endfor %}

# Office Hours

<table>
  <thead>
    <tr>
      <th>Staff</th>
      <th>Day &amp; Time</th>
      <th>Location</th>
    </tr>
  </thead>
  <tbody>
    {% for oh in variables.instructor.office_hours %}
    <tr>
      <td>{{ variables.instructor.name }}</td>
      <td>{{ oh.day }} {{ oh.time }}</td>
      <td>{{ oh.location }}</td>
    </tr>
    {% endfor %}

    {% for row in variables.teaching_assistants %}
      {% for oh in row.office_hours %}
    <tr>
      <td>{{ row.name }}</td>
      <td>{{ oh.day }} {{ oh.time }}</td>
      <td>{{ oh.location }}</td>
    </tr>
      {% endfor %}
    {% endfor %}

    {% for row in variables.instructional_assistants %}
      {% for oh in row.office_hours %}
    <tr>
      <td>{{ row.name }}</td>
      <td>{{ oh.day }} {{ oh.time }}</td>
      <td>{{ oh.location }}</td>
    </tr>
      {% endfor %}
    {% endfor %}
  </tbody>
</table>