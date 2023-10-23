---
layout: default
title: Home
---

## Overview

I am a PhD graduate in computer sciences, currently searching for a postdoc where to apply data analysis or algorithmic concepts to climate change research and mitigation.
I defended my thesis in the computer science lab [LIP6](https://www.lip6.fr/) of Sorbonne University in Paris, under the supervision of Lionel Tabourier and Clémence Magnien in the [Complex Networks](https://www.complexnetworks.fr/) team.
It focussed on scalable graph algorithms applied on real-world datasets, specifically on finding node orderings that improve specific algorithms in practice. I also worked on citation networks and scientific trajectories as a visiting student in a [data analysis lab](https://interactiondatalab.com/). Before that, I graduated from [ENS Lyon](http://www.ens-lyon.fr/LIP/) in computer sciences and complex systems where I did research on dynamic networks.

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
* Sustainability: renewable energy, local food networks, low consumption. Volunteer in the NGO that installs solar panels on Parisian roofs to monitor operations and solicit new surfaces.
