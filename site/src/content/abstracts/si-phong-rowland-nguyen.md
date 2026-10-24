---
title: 'Beyond Single-View Wildfire Susceptibility Mapping: A Trust- and Uncertainty-Aware Multi-View Framework'
presenter: Si Phong (Rowland) Nguyen
affiliation: Monash University
coauthors:
- Xuan Zhu
- Lan Du
session: S6 · Weather extremes and water
slot: Day 2 (Fri 6 Nov) · 12:45–13:00 · Room 1
---

Wildfire susceptibility is shaped by a diverse set of interacting environmental and human influences. Terrain, vegetation and fuel, anthropogenic activity, and climate describe different aspects of the conditions associated with wildfire occurrence, yet they are commonly brought together as a single set of model inputs. This can obscure the distinct information carried by each source, particularly when their relevance, reliability, or level of uncertainty differs.

This work explores an alternative based on multi-view representation, where related variables are organised into separate but complementary views and retained independently until model fusion. Building on methods developed for trust-aware multi-view classification, the framework extends this idea by considering not only what each view contributes but also how much its contribution should be trusted and how certain the resulting prediction is. In this formulation, trust and uncertainty play different roles: trust regulates the influence of individual views during fusion, while uncertainty reflects the strength of the evidence supporting the final prediction.

Wildfire susceptibility provides a useful setting in which to examine this approach because its predictors are inherently heterogeneous. A preliminary prototype for Alpine Shire, Victoria, represents the landscape through four views: topographic, vegetation and fuel, anthropogenic, and climatic. Each view produces its own evidence for wildfire susceptibility, together with information that allows its reliability to be considered before the views are combined. The fused output therefore retains a connection to the contributing information sources while providing both a susceptibility estimate and an associated measure of uncertainty.

Rather than treating the prototype as a final predictive model, it is used here to demonstrate how principles from multi-view classification can be translated into a spatial wildfire context. The broader aim is to develop a modelling framework in which heterogeneous wildfire information is represented explicitly, conflicting or less reliable sources can be moderated during fusion, and uncertainty forms part of the prediction itself rather than being considered only after modelling.
