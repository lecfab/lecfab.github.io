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

* [_Quality certification of heuristics on real-world graphs_](/public/pdf/Lecuyer_2022_Quality-certification.pdf). Fabrice Lécuyer (submitted 2022)

* [_Certifier la qualité d’une heuristique sur graphs réels_](/public/pdf/Lecuyer_2022_JGA.pdf). Fabrice Lécuyer ([JGA](https://jga2022.sciencesconf.org/) 2022)

* [_Tailored vertex ordering for faster triangle listing in large graphs_](https://arxiv.org/abs/2203.04774). Fabrice Lécuyer, Louis Jachiet, Clémence Magnien, Lionel Tabourier ([ALENEX](https://www.siam.org/conferences/cm/conference/alenex23) 2023 and [MLG](http://www.mlgworkshop.org/2022/) workshop of [KDD](https://www.kdd.org/kdd2022/) 2022)

* [_Grands réseaux complexes : mettre de l’ordre dans les triangles_](/public/pdf/Lecuyer_2022_FRCCS.pdf). Fabrice Lécuyer, Louis Jachiet, Clémence Magnien, Lionel Tabourier ([FRCCS](https://iscpif.fr/frccs2022/) 2022)

* [_[Replication] Speedup Graph Processing by Graph Ordering_](https://doi.org/10.5281/zenodo.4836230). Fabrice Lécuyer, Maximilien Danisch, Lionel Tabourier ([ReScience](http://rescience.github.io), 2021)

## Research reports
* [_Community detection in fine-grained dynamical networks_](/public/pdf/Lecuyer_2020_Dynamical-community-detection.pdf). Fabrice Lécuyer, Rémy Cazabet (Internship in Lyon, 2020)

* [_Model of the Hospital Network and Health Trajectories_](/public/pdf/Lecuyer_2017_Hospital-network-model.pdf). Fabrice Lécuyer, Marc Santolini, Amar Dhand, Sean Cornelius, Albert-László Barabási (Internship in Boston, 2017)

* [_Introduction de données quantitatives dans la modélisation qualitative des régulations biologiques_](/public/pdf/Lecuyer_2016_Reseaux-regulation-biologique.pdf). Fabrice Lécuyer, Olivier Roux (Internship in Nantes, 2016)


## Teaching

* 2020, 2021, 2022: Python, L1.
* 2021, 2022: Algorithmique, L2.
* 2019: oral interrogations in physics, PCSI/PC.

## Other interests

* Instrumental music: piano playing and teaching, accordion, viola, classical choir.
* Programming: developed a PHP/SQL online game and worked as a frontend developer for a car-fleet management system.
* Linguistics
* Sustainability: renewable energy, local food networks, low consumption.
