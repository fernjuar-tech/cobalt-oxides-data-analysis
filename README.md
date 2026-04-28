# Cobalt Oxides – Formation Energy Analysis

## Overview

This project presents a data-driven analysis of formation energies in cobalt oxide systems obtained from density functional theory (DFT) simulations.

The goal is to explore how formation energy depends on:

- composition (Co/O ratio)
- hydrogen content (nH)
- chemical environment (different reservoir conditions)

## Dataset

The dataset contains processed simulation results with the following variables:

- ratioCo/O: ratio between cobalt and oxygen atoms
- Eform1: formation energy under O₂/H₂ reservoir conditions
- Eform3: formation energy under H₂/H₂O reservoir conditions
- nH: number of hydrogen atoms (discrete variable)

## Analysis

The analysis focuses on visualizing trends in formation energy as a function of composition and hydrogen content.

Two scenarios are compared:
- O₂ / H₂ reservoirs
- H₂ / H₂O reservoirs

Scatter plots are used to:

- identify trends with respect to composition
- distinguish energy groupings based on hydrogen content
- compare the influence of different chemical environments

## Key Insights

Formation energy shows a clear dependence on the Co/O ratio

Hydrogen content (nH) introduces distinct groupings in the energy landscape

The choice of chemical reservoir significantly affects the stability of configurations

Different environmental conditions lead to noticeably different energetic trends

## Tools

Python

pandas

matplotlib / seaborn

## Purpose

This project demonstrates how simulation data can be processed, visualized, and interpreted using a data science approach.
