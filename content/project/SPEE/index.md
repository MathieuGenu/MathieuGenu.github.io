---
title: SPEE
excerpt: >-
  Shiny application summarizing analysis of aerial survey SPEE, a survey which
  occured in french atlantic ocean.
date: '2025-02-28'
categories:
  - R
  - shiny
layout: single
featured: true
draft: false
format:
  hugo-md:
    code-fold: true
include-in-header:
  text: |
    <style type="text/css">
    .mw7 {
      max-width: 100rem;
    }
    .ph4-l {
      padding: 0rem;
    }
    </style>
---


<style type="text/css">
.mw7 {
  max-width: 100rem;
}
.ph4-l {
  padding: 0rem;
}
</style>


This shiny app gather key results of the SPEE aerial survey which occured during each season of 2019 to 2020 and winter 2021 (more informaton [here](https://www.observatoire-pelagis.cnrs.fr/pelagis-2/les-programmes/spee/)).

Among this results :

-   Raw sightings of megafauna
-   Observation rate
-   DSM prediction densities
-   Relative index of densities which correspond to the mean percentage of occupation of each cell of the grid by species

<iframe height="1000px" width="100%" frameborder="no" src="https://pelabox.univ-lr.fr/pelagis/SPEE_3/">
</iframe>
