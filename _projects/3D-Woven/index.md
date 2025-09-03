---
layout: post
title: "Finite Element Analysis of 3D Woven Composite"
description: "Engineered an indigenous 8-layer 3D woven carbon/epoxy in plain-weave architecture for aircraft L-stringers. Applied CLT and micro/macro-mechanical modeling, with CATIA-based geometry and ANSYS APDL analysis, demonstrating +22% Y-load capacity and +35% out-of-plane capacity over 2D laminates; findings published (Taylor & Francis, DOI: 10.1201/9781003216742)."
skills: 
  - Composites
  - Structural analysis
  - CLT (Classical Laminate Theory)
  - FEM (ANSYS, ABAQUS)
  - CATIA V5
  - TexGen
  - Stress analysis
  - Material characterization
  - Structural testing
  - Scientific writing
main-image: /images/3d_woven/main.jpg
---

## Overview
This project designed and analyzed an **8-layer 3D woven CFRP** (plain-weave) tailored for **aircraft wing L-stringers**, targeting improved **out-of-plane strength and damage tolerance** relative to 2D laminates.

## Objectives
- Derive laminate stiffness for an orthogonal 3D woven architecture (CLT + micro/macro mechanics).  
- Build a **CAD + FEA** workflow to evaluate load capacity in **Y** (in-plane) and **Z** (out-of-plane) directions.  
- Benchmark against 2D laminated baselines.

## Methods
- **Constitutive modeling:** CLT for laminate A/B/D matrices; micro/macro links via **TexGen-style yarn geometry** and rule-of-mixtures refinements.  
- **CAD:** L-stringer geometry and layup references in **CATIA V5**.  
- **FEA:** Static structural analyses in **ANSYS APDL**; assessment of interlaminar response and local stress fields.

## Results & Metrics
- **+22%** increase in **Y-direction** load capacity.  
- **+35%** increase in **Z-direction** (out-of-plane) capacity vs. 2D laminates.  
- Work **published**: Taylor & Francis (**DOI: 10.1201/9781003216742**).

## What to look for in images
- Yarn-level schematic and equivalent orthotropic ply properties.  
- CATIA L-stringer geometry and FE mesh.  
- Load–displacement curves comparing 3D vs 2D laminates.

## Images
{% include image-gallery.html images="/3d_woven.jpg, /images/3d_woven/catia.jpg, /images/3d_woven/ansys_results.jpg" height="400" %}

## Notes
- Material: carbon/epoxy; woven architecture tuned for **interlaminar performance**.  
- Failure interrogation with classical criteria where applicable; extended out-of-plane capacity is the principal gain.

