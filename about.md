---
layout: page
title: TopModel
subtitle: Multi-parameter Topology for Machine Learning Models
permalink: /
redirect_from:
  - /about/
  - /about.html
---

# General Presentation

TopModel is an ANR JCJC grant of four years (2023-2027) that aims at studying the incorporation of multi-parameter topology to machine learning models for both single-cell and cosmological data. 

# Abstract 

The central tenet of this project is the use of multiparameter topological data analysis for machine learning models, for both regularizing and monitoring these models, and for the automatic generation of new features and descriptors to feed these models with. On the theoretical front, a lot of efforts will be devoted to the development, implementation and generalization of standard topological data analysis techniques, who (for the most part) can only study the topological variations of at most one parameter (such as the data scale), so as to make them suitable for the study of the topological variations of several parameters jointly (such as density and scale, marker genes). Then, the focus will be on specific applications, for which topological data analysis is known to be relevant and efficient, of these new multiparameter topological data analysis methods for machine learning models. More precisely, we will emphasize the usefulness of our new tools on data sets from cosmology (large scale structures of the Universe) and biology (single-cell sequencing, mass cytometry).

{% for post in site.wps %}
    {% include wps.html %}
{% endfor %}

