---
title: "PERSUE Lab - Team"
layout: gridlay
excerpt: "Persue Lab: Team members"
sitemap: false
permalink: /team/
---

Group Members

We are looking for new PhD students, Postdocs, and Master students to join the team [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) !

Jump to staff, master and bachelor students, alumni, administrative support, lab visitors.

Staff

{% assign number_printed = 0 %} {% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

{% endif %}

{{ member.name }}

{{ member.info }}
{% if member.number_educ == 1 %}

{{ member.education1 }}
{% endif %}
{% if member.number_educ == 2 %}

{{ member.education1 | markdownify}}
{{ member.education2 | markdownify}}
{% endif %}
{% if member.number_educ == 3 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{% endif %}
{% if member.number_educ == 4 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{{ member.education4 }}
{% endif %}
{% if member.number_educ == 5 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{{ member.education4 }}
{{ member.education5 }}
{% endif %}
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %} {% if even_odd == 1 %}

{% endif %}
Master and Bachelor Students

{% assign number_printed = 0 %} {% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

{% endif %}
{{ member.name }}

{{ member.info }}
{% if member.number_educ == 1 %}

{{ member.education1 }}
{% endif %}
{% if member.number_educ == 2 %}

{{ member.education1 }}
{{ member.education2 }}
{% endif %}
{% if member.number_educ == 3 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{% endif %}
{% if member.number_educ == 4 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{{ member.education4 }}
{% endif %}
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %} {% if even_odd == 1 %}

{% endif %}
