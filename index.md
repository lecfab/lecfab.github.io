---
layout: default
title: Home
---

## Overview

I am a PhD student in the computer science lab [LIP6](https://www.lip6.fr/) of Sorbonne University in Paris, under the supervision of Lionel Tabourier and Clémence Magnien in the [Complex Networks](https://www.complexnetworks.fr/) team.
I'm interested in scalable graph algorithms applied on real-world datasets, with a focus on finding node orderings that improve specific algorithms in practice. I also work on citation networks and scientific trajectories as a visiting student in a [data analysis lab](https://interactiondatalab.com/). Before that, I graduated from [ENS Lyon](http://www.ens-lyon.fr/LIP/) in computer sciences and complex systems.

Feel free to contact me by email!

## Publications and talks
<!--  | where:"ref", page.ref | sort: 'lang' -->
{% assign publis=site.data.academia %}
{% for publi in publis %}
* {% if publi.link %} [_{{publi.title}}_]({{publi.link}}), {% else %} _{{publi.title}}_, {% endif %}
{{publi.published}} {{publi.year}}.
{% if publi.authors %} {{publi.authors}}. {% endif %} {{publi.comment}}
{% endfor %}

## Research reports
{% assign internships=site.data.research %}
{% for internship in internships | where_exp: "item", "item.link != empty" %}
{% if internship.link %}
*  [_{{internship.title}}_]({{internship.link}}), {{internship.dates}}.
Internship in {{internship.location}} with {{internship.supervisors}}.
{% endif %}
{% endfor %}


## Teaching

* 2020, 2021, 2022: Python, L1.
* 2021, 2022: Algorithmique, L2.
* 2019: oral interrogations in physics, PCSI/PC.

## Other interests

* Instrumental music: piano playing and teaching, accordion, viola, classical choir.
* Programming: developed a PHP/SQL online game and worked as a frontend developer for a car-fleet management system.
* Linguistics
* Sustainability: renewable energy, local food networks, low consumption.
