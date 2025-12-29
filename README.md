# mRCS-GRL-Data
Official simulated data for the paper "mRCS-GRL: A Lightweight High-Precision Multi-Target RCS Prediction Algorithm".

## Introduction
This repository contains the comprehensive electromagnetic scattering simulated data constructed using Altair FEKO. The dataset covers three typical electromagnetic scattering regimes:
**Rayleigh Region (5 MHz)**
**Resonant Region (400 MHz)**
**Optical Region (1 GHz)**

It includes Monostatic RCS simulation data for multi-target formations (Spheres, Cones, Cubes) under various spatial topologies (Linear, Oblique, V-shaped).

## Dataset Structure
The data is organized by frequency regimes. Each file contains the RCS response concerning the azimuth angle.

mRCS-GRL-Data/
├── 01_5MHz/      # Data for low-frequency smooth scattering
├── 02_400MHz/    # Data for complex interference patterns
└── 03_1GHz/       # Data for high-frequency specular reflections
