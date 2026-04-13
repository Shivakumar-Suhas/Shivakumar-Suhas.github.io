---
layout: post
title: "Machine Learning-Driven Prediction of Material Properties for AFP Laminates with Defects"
description: "Characterized AFP laminates with gaps/overlaps (tension, bending, compression), built ABAQUS ply-level models with explicit defect geometries, Hashin initiation, and VCCT/CZM delamination. Achieved ~92.7% correlation to tests; automated workflows (MATLAB/Python) and trained an ANN (R²=0.97, MAE=0.0225) for rapid property prediction."
skills: 
  - AFP (Automated Fiber Placement)
  - Failure analysis
  - ABAQUS
  - VCCT/CZM
  - Python & MATLAB scripting
  - Structural testing
  - Fracture mechanics
  - Data analysis
  - Material characterization
main-image: /AFP.png
---

## Background
AFP introduces **manufacturing defects** (gaps, overlaps, tow drops) that can degrade stiffness and strength. Understanding **defect tolerance** requires consistent testing and validated FE models.

## Objectives
- Quantify stiffness/strength knockdowns for **gaps and overlaps** under **tension/compression/bending**.  
- Create **ply-level ABAQUS models** with explicit defect geometry and inter/intralaminar failure.  
- Provide **allowables/knockdown curves** and a fast-running predictor.

## Experimental Program
- Coupons: pristine vs. defective; six configurations by **defect type/location**.  
- Outputs: stress–strain, strength, stiffness; fracture observations (initiation/propagation).

## Simulation & Automation
- **FEA:** Hashin failure initiation + damage evolution (intralaminar), **VCCT/CZM** for delamination (interlaminar).  
- **Batch automation:** geometry/mesh/material/BC scripting in **Python/MATLAB**; Excel/CSV export for comparison.  
- **Validation:** ~**92.7%** correlation (strength/stiffness/load–displacement).

## Surrogate Model (ANN)
- ANN trained on **synthetic data** from validated FE; achieved **R² = 0.97**, **MAE = 0.0225** across load cases.  
- Use case: rapid screening of **defect size/location** impacts on laminate properties.

## Results
- **Residual-strength knockdown curves** vs. defect size & location.  
- Process insight for **defect-tolerant design** and **NC programming** of AFP to minimize critical defects.

## What to look for in images
- **Defective laminate behavior:** Failure modes under compression highlighting defect sensitivity.  
- **Defect configurations:** Placement of gaps/overlaps across different ply orientations (0°, 90°, ±45°).  
- **FE boundary conditions:** Setup for tension and bending simulations ensuring representative loading.  
- **Simulation results:** Strain field and displacement distribution across configurations showing defect-driven response variations.

## Images
{% include image-gallery.html images="/Compressiontest.jpg, /Configuration.png, /tensionbc.png, /BC of Bending.png, /tensionsimu.png" height="400" %}

## Notes
- The **cohesive/VCCT** setup captures **crack initiation and growth** across interfaces.  
- NC programs for AFP layup were prepared to **introduce controlled defects** for testing.


