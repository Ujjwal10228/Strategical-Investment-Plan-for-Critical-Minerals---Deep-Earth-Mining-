# Strategical-Investment-Plan-for-Critical-Minerals---Deep-Earth-Mining-

🎯 **Main Task**

Prepare an investment plan optimizing:

Location (A, B, C)

Depth (0–20 km)

Year horizon (5, 10, 15 years)

**Goal**: Maximize cumulative profit over 5, 10, and 15 years.

**Profit = Σ massₘ,ₗ,ₗ × ( priceₘ,ᵧ – ( costₗ,ₗ + refining_costₗ,ₗ ) )**

Where:

**m** → mineral

**l** → location

**d** → depth

**y** → year horizon

Supply-demand constraints:
If extraction exceeds the demand–supply gap, prices fall.
Price remains fixed only if:
demand < new_supply


- requirements.txt	Dependencies (pandas, numpy, scipy, matplotlib, seaborn, pulp, openpyxl)
- task1_task2_industry_analysis.ipynb	Mining industry overview + ecological impacts 
- task3_depth_optimization.ipynb	Depth optimization model for all locations 
- task4_mineral_extraction.ipynb	Mineral selection optimization for Location A 
- task5_custom_strategy.ipynb	Custom 15-year strategic investment plan 

### Content Summary
**Task 1 & 2 Notebook**
Mining operations pipeline (Licensing → Exploration → Extraction → Concentration → Refining → Logistics)
Cost drivers analysis with visualizations
6 ecological impacts identified with risk assessment
Mitigation strategies for groundwater, heat/pressure, chemical leakage, and seismic risks

**Task 3 Notebook**
Calculates demand-supply gaps for all minerals
Identifies top 4 minerals by gap size
Computes profit at each depth (0-20km) for Locations A, B, C
Outputs optimal depth per location per horizon (5/10/15 years)

**Task 4 Notebook**
Uses optimal depths from Task 3
Includes additional logistics costs per number of minerals
Greedy optimization to select minerals maximizing profit
Results saved to task4_optimization_results.csv

**Task 5 Notebook**
Phased depth progression strategy
Mineral portfolio diversification (Core/Stable/Growth)
Competitive advantage leveraging with ESG positioning
15-year strategic roadmap visualization
