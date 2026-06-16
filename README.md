
# Marine Cloud Brightening

**Authors:** Lena Predl, Enes Köksal, Julian Kragler and Raúl Muñoz Ruiz.

This repository contains analysis notebooks and runscript configurations for an idealized marine cloud brightening study using the ICON climate model in a slab-ocean setup.

## Project overview

The aim of this project is to investigate the climatic response to marine cloud brightening (MCB). In the simulations, MCB is represented by increasing the cloud droplet number concentration over ocean surfaces. Additional experiments with doubled CO₂ are included to compare the MCB response under stronger greenhouse-gas forcing.

The analysis focuses on four main climate variables:

- Temperature
- Precipitation
- Radiative fluxes
- Cloud cover

## Repository structure

```text
Marine-Cloud-Brightening/
│
├── CloudCover/
│   └── cloudwork.ipynb
│
├── Precipitation/
│   └── Precipitation_analysis.ipynb
│
├── RadiativeFluxes/
│   └── radiation_plots.ipynb
│
├── Temperature/
│   └── temperature_analysis.ipynb
│
├── runscripts/
│   ├── exp.slab187_1co2.run
│   ├── exp.slab187_2co2.run
│   ├── exp.slab375_2co2.run
│   ├── exp.slabcn2sea375.run
│   ├── exp.slabcn560.run
│   └── exp.slabcn560doubledco2.run
│
└── README.md
