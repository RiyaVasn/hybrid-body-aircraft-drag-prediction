# hybrid-body-aircraft-drag-prediction
Research and CFD validation on the drag coefficient prediction of a hybrid body aircraft design using RSM, ANOVA, and advanced composite materials.

# Prediction of Drag Coefficient of a Hybrid Body Design of Aircraft

This repository contains the analysis, design files, and methodology for the aerodynamic optimization of a hybrid body aircraft design. The project explores the integration of hybrid wing-body (HWB) configurations, Response Surface Methodology (RSM), and advanced composite materials to improve fuel economy and reduce the drag coefficient.

## Key Contributions

* **CAD Modeling:** Developed the hybrid blended-body aircraft geometry in SolidWorks.
* **Design of Experiments (DoE):** Used Central Composite Design (CCD) under Response Surface Methodology (RSM) to structure CFD simulations.
* **Statistical Analysis:** Applied Analysis of Variance (ANOVA) in MINITAB to quantify the impact of variables on the drag coefficient.
* **Material Optimization:** Proposed and analyzed a lightweight material combination consisting of Glass Fiber Reinforced Polymer (GFRP), Carbon Fiber Reinforced Polymer (CFRP), and 10% Graphene Nano Powder.
* **CFD Validation:** Validated aerodynamic performance using ANSYS FLUENT, showing less than a 5% deviation between predictive and simulated results.

## Technical Stack & Tools Used

* **3D & 2D CAD:** SolidWorks, Airfoil Tools
* **Meshing & Simulation:** ANSYS, ANSYS FLUENT (RANS approach)
* **Statistical Modeling & Optimization:** MINITAB, Response Surface Methodology (RSM)
* **Material Evaluation:** Composite nanomaterials and shape memory polymers

## Repository Structure

```text
├── paper.pdf                    # Published research paper and methodology
├── code/                        # Simulation setup and analysis scripts
├── data/                        # ANOVA and RSM design matrices
└── figures/                     # Main Effects plots, contours, and CAD renders
