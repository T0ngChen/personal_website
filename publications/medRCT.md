---
author: <b>Tong Chen</b>, S. Ghazaleh Dashti, Margarita Moreno-Betancur
date: 2025-03-13
title: "medRCT: Causal mediation analysis estimating interventional effects mapped to a target trial in R"
details: <em>Journal of Open Source Software</em>, 10(110), 8063
doi: 10.21105/joss.08063
categories: Methodology
---

# Summary

The R package `medRCT` for causal mediation analysis supports the
estimation of interventional effects (VanderWeele, Vansteelandt, and
Robins 2014), specifically interventional effects that are defined such
that they map explicitly to a “target trial” (Hernán and Robins 2016),
as recently proposed by Moreno-Betancur et al. (2021). In the target
trial, the treatment strategies are specified to reflect hypothetical
interventions targeting and thus shifting the joint distribution of the
mediators. `medRCT` can accommodate any number of potentially correlated
mediators, including mediators that are not of primary interest but that
are intermediate (exposure-induced) mediator-outcome confounders.