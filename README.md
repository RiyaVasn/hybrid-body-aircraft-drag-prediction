# hybrid-body-aircraft-drag-prediction
Research and CFD validation on the drag coefficient prediction of a hybrid body aircraft design using RSM, ANOVA, and advanced composite materials.

# Prediction of Drag Coefficient of a Hybrid Body Design of Aircraft

This repository contains the analysis, design files, and methodology for the aerodynamic optimization of a hybrid body aircraft design. The project explores the integration of hybrid wing-body (HWB) configurations, Response Surface Methodology (RSM), and advanced composite materials to improve fuel economy and reduce the drag coefficient.

## Visualizations & Analysis
| FEA Procedure Flowchart |
<img width="760" height="513" alt="FEA Procedure" src="https://github.com/user-attachments/assets/60a0ea2e-eae8-4b7b-ac2c-7e317c159b55" />

| Hybrid Body Aircraft Views |
<img width="1157" height="197" alt="image" src="https://github.com/user-attachments/assets/fc76f964-e6c6-4bea-a5ca-a1022d441db8" />

| Main Effects Plot |
<img width="867" height="533" alt="image" src="https://github.com/user-attachments/assets/18b57cb8-e132-45b2-b941-f980feb7baa8" />

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

## Authors
Shreya Viswanath, Riya Vasan, Dr. Venkatachalam Gopalan, Nilesh Satonkar


## Repository Structure

```text
├── paper.pdf                    # Published research paper and methodology
├── code/                        # Simulation setup and analysis scripts
├── data/                        # ANOVA and RSM design matrices
└── figures/                     # Main Effects plots, contours, and CAD renders

