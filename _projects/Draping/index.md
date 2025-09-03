---
layout: post
title: "Implementation of a Machine-Learning Model to Optimize Composite Manufacturing"
description: "With Premium AEROTEC, optimized draping/preforming of NCFs by combining experiments and ABAQUS drape simulation (87% predictive accuracy). Processed datasets (compaction, shear, wrinkle zones) and trained ML models reaching R²=0.94 and MAE=0.005 to reduce trial-and-error and material waste."
skills: 
  - Composite manufacturing
  - Draping simulation
  - Abaqus
  - Process optimization
  - Data analysis
  - Python scripting
  - Machine learning
  - Stress analysis
  - Scientific writing
main-image: /images/ml_draping/main.jpg
---

## Background
Non-Crimp Fabrics (NCFs) are widely used in aerospace preforms but are prone to **wrinkles and fiber shear** during draping, driving rework and scrap. This project built a **test–simulation–ML** loop to predict and mitigate such defects.

## Objectives
- Quantify **fiber slippage, shear angle**, and wrinkle onset under varied compaction and boundary conditions.  
- Build a **finite-element draping model** to forecast wrinkle-prone regions.  
- Train ML models to accelerate **process window selection**.

## Experimental Campaign
- Draping trials across **compaction loads**, tool curvatures, and clamping conditions.  
- Measurements: **shear angle**, out-of-plane wrinkling, and local thickness variations.

## Simulation
- **ABAQUS-based** draping FE (membrane/biaxial response tuned to NCF behavior).  
- Calibrated to achieve **~87%** predictive accuracy for deformation patterns and wrinkle zones.

## Data → ML
- Features: compaction load, curvature radius, boundary conditions, shear metrics, wrinkle flags.  
- Models: evaluated via AutoML; best models achieved **R² = 0.94**, **MAE = 0.005** for wrinkle prediction/severity scoring.

## Results & Impact
- Reduced **experimental iterations**, earlier detection of problematic regions, and **material savings**.  
- Delivered a **decision aid** for preform process parameters.

## Images
{% include image-gallery.html images="/images/ml_draping/bench.jpg, /images/ml_draping/fe_shear_map.jpg, /images/ml_draping/wrinkle_pred_vs_obs.jpg" height="400" %}

## Notes
- Code: Python for data prep/feature engineering; ABAQUS scripts for batch runs.  
- The ML layer complements—not replaces—physics-based drape analysis.


