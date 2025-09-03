---
layout: post
title: "Structural and Modal Analysis of Composite Rotor Blades"
description: "CATIA-based rotor geometry and ply-level FEM in ABAQUS using a [0/±45/90]s carbon/epoxy layup; structural simulations for hover and cyclic loading with modal analysis of flap/lag/torsion. Achieved ~28% weight reduction vs metallic baseline while maintaining FOS ≥ 2 (Hashin)."
skills: 
  - Composite structures
  - FEM (ABAQUS)
  - CATIA V5
  - Modal analysis
  - Rotordynamics
  - Structural analysis
  - CAD modeling
main-image: /images/rotor_blade/main.jpg
---

## Overview
This study evaluates a **carbon/epoxy composite rotor blade** relative to a metallic baseline, targeting **mass reduction** while preserving **strength and dynamic performance**.

## Model Definition
- **CAD:** detailed planform/twist/airfoil geometry in **CATIA V5**.  
- **Layup:** **[0/±45/90]s** (spar/skin tailored for torsion/bending).  
- **Material:** carbon/epoxy with orthotropic properties.

## Loads & Boundary Conditions
- **Hover** and **cyclic** operational envelopes considered.  
- Root boundary conditions to reflect hub constraints.

## Analyses
- **Static strength** with **Hashin** failure initiation and progressive damage.  
- **Modal analysis:** extraction of flap/lag/torsion modes and mode shapes.

## Results & Metrics
- **~28% weight reduction** vs metallic baseline.  
- **FOS ≥ 2** across operating cases (Hashin checks).  
- Modal analysis confirms adequate separation of primary modes for stability.

## Notes
- Further extensions can include **aeroelastic coupling** and **transient loads** (maneuver/cycling), as needed.  
- Manufacturing constraints (ply drape, minimum steering radii) can be integrated as a follow-on.



