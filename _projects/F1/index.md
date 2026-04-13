---
layout: post
title: "Composite Rear Wing – Structural Design and Optimization (Formula 1)"
description: "CFD-driven structural design of a composite Formula 1 rear wing using CATIA V5, ANSYS Fluent, and ABAQUS. Laminate-level optimization with Hashin and Tsai–Wu failure criteria achieved ~20% mass reduction under FIA load conditions."

skills: 
  - Composite Structures (CFRP)
  - Aerodynamic Load Analysis (CFD – ANSYS Fluent)
  - FEM (ABAQUS)
  - CAD Modeling (CATIA V5)
  - Laminate Optimization
  - Structural & Stress Analysis
  - Failure Criteria (Hashin, Tsai–Wu)
  - Aero-Structural Coupling
  - Python / MATLAB (Workflow Automation)
  - Parametric Design Studies

main-image: /F1rear.jpg
---

## Overview
This work focuses on the **aero-structural design and optimization of a CFRP Formula 1 rear wing**, targeting **maximum stiffness-to-weight efficiency** under **FIA regulatory load conditions**. The study integrates **aerodynamic load extraction, laminate-level structural analysis, and optimization** to develop a lightweight yet structurally robust design.

## Geometry & Aerodynamic Analysis
- Developed a detailed **3D CAD model** of the rear wing using **CATIA V5**, including main plane and aerodynamic profiles.  
- Performed **CFD analysis (ANSYS Fluent)** to evaluate **pressure distribution and aerodynamic loading** across wing surfaces.  
- Extracted aerodynamic loads and mapped them onto the structural model for further analysis.

## Structural Modeling & Laminate Design
- Built a **laminate-level FEM in ABAQUS**, representing composite skins and internal structural elements.  
- Designed CFRP laminates using **ply-level stacking sequences**, optimizing **fiber orientations and thickness distribution**.  
- Considered **combined aerodynamic and structural loading**, ensuring compliance with stiffness and displacement constraints.

## Analyses
- **Static structural analysis** to evaluate stress distribution and deformation behavior under FIA load cases.  
- **Failure analysis** using **Hashin and Tsai–Wu criteria** to predict matrix cracking, fiber failure, and overall laminate failure.  
- Conducted **parametric studies** on ply orientations and thickness to assess stiffness–weight trade-offs.

## Optimization & Automation
- Developed **Python and MATLAB workflows** to streamline **CFD-to-FEA data transfer**, enabling rapid design iterations.  
- Implemented iterative optimization loops to refine laminate configurations for improved performance.

## Results & Key Outcomes
- Achieved **~20% mass reduction** compared to baseline design while maintaining **structural integrity and displacement limits**.  
- Optimized laminate configurations improved **load distribution and stiffness under aerodynamic loading**.  
- Identified critical regions prone to failure, enabling targeted reinforcement and efficient material usage.

## What to look for in images
- **Rear wing CAD model:** Aerodynamic profile and geometric definition of the main elements, including smooth surface transitions and curvature.  
- **Structural response (main flap):** Qualitative stress/deformation distribution under aerodynamic loading, highlighting load-carrying regions.

## Images
{% include image-gallery.html images="/rearwingcad.png, /flap1result.png" height="400" %}

## Notes
- Study assumes **steady aerodynamic conditions** representative of high-speed operation.  
- Further work can include **transient loading, aeroelastic effects, and detailed joint/mounting analysis**.  
- Manufacturing constraints such as **ply draping and curvature effects** can be incorporated in advanced design stages.
