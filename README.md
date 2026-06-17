![Method](https://img.shields.io/badge/Method-MILP_Optimization-blue?style=for-the-badge&logo=mathworks&logoColor=white)
![Tool](https://img.shields.io/badge/Tool-MATLAB-orange?style=for-the-badge&logo=matlab&logoColor=white)
![Analysis](https://img.shields.io/badge/Goal-Cost_Minimization-red?style=for-the-badge&logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=github&logoColor=white)
# Electrical Energy Analysis: Generation Expansion Planning (Phase 2)

## Project Overview
This repository contains the second phase of the Generation Expansion Planning (GEP) project. While Phase 1 focused on strategic assessment, this phase implements the mathematical optimization models in **MATLAB** to determine the most cost-effective and reliable energy mix over a 20-year planning horizon.

## Methodology & Implementation
- **Optimization Modeling:** Developed an objective function to minimize total system costs, including capital investment, operation and maintenance (O&M), and fuel costs.
- **Constraints Handling:** Implemented constraints for reserve margins, emission limits, and hourly capacity requirements using MATLAB optimization solvers.
- **Sensitivity Analysis:** Evaluated the system response to variations in fuel prices and carbon tax policies.

## Technical Details
- **Tool:** MATLAB
- **Key Modules:** - Data pre-processing script (`init_data.m`)
    - Optimization solver implementation (`main_optimization.m`)
    - Result visualization & plotting (`plot_results.m`)
- **Core Algorithms:** Linear/Mixed-Integer Programming (LP/MILP) for cost minimization.

## Repository Structure
- `/Code`: All MATLAB scripts and model files.
- `/Plots`: Generated graphs, including energy mix evolution and cost distribution charts.
- `/Report`: Technical documentation of the model formulation and simulation results.

---
*Developed for Electrical Energy Analysis Course | Sharif University of Technology*
