# Reconstructing the J/ψ Particle from CMS Open Data

## Project Overview

This project reconstructs the J/ψ particle using its decay into an oppositely charged muon pair:

J/ψ → μ⁺ + μ⁻

Using particle momentum information from CMS Open Data, the analysis reconstructs the four-momentum of muons, calculates the invariant mass of muon pairs, and searches for the characteristic J/ψ mass peak.

## Project Goals

- Understand the structure of particle physics event data.
- Work with ROOT files using Uproot and Awkward Array.
- Explore CMS collision data.
- Identify and select muon candidates.
- Construct muon four-momenta.
- Calculate dimuon invariant mass.
- Visualize the invariant mass distribution.
- Identify and interpret the J/ψ signal.

## Physics Background

The J/ψ particle can decay into:

J/ψ → μ⁺ + μ⁻

For each muon pair, the invariant mass is calculated using:

m² = E² - pₓ² - pᵧ² - p_z²

For a two-muon system:

mμμ² =
(E₁ + E₂)²
- (pₓ₁ + pₓ₂)²
- (pᵧ₁ + pᵧ₂)²
- (p_z₁ + p_z₂)²

A peak in the dimuon invariant mass distribution provides evidence for J/ψ production.

## Project Structure

```text
CERN Project/
│
├── notebooks/      # Exploratory and analysis notebooks
├── src/            # Reusable Python functions
├── data/           # Local datasets (not tracked by Git)
├── results/
│   └── figures/    # Generated figures
│
├── README.md
├── requirements.txt
└── .gitignore