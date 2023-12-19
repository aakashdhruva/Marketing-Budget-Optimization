# Marketing Budget Optimization Using Linear Programming

## Project Overview
This project involves the development of a linear programming model to optimize the allocation of a marketing budget across various channels. The goal is to maximize the return on investment (ROI) while adhering to specific constraints.

## Problem Description
Marketing budgets are crucial for company growth, yet their effectiveness varies greatly. This project explores the optimization of budget allocation across different marketing platforms, considering constraints and varying ROI estimates.

## Data and ROI Estimates
The project uses ROI estimates for different marketing mediums such as print, TV, Facebook, Email, etc. These estimates are crucial in determining the optimal allocation of the marketing budget.

## Methodology

### Linear Programming Formulation
The problem is formulated as a linear programming model with an objective function to maximize the total ROI. The model includes constraints such as budget limits for each platform and specific allocation ratios between different groups of platforms.

### Analysis with Gurobi
Gurobi, an advanced optimization solver, is employed to find the optimal budget allocation. The solver effectively handles the linear programming model to output the most efficient allocation strategy.

## Comparative Analysis
The project compares the optimal allocations derived from two different sets of ROI data. It examines the impact of these differences on the overall marketing strategy and budget effectiveness.

## Sensitivity Analysis
A sensitivity analysis is conducted to understand how changes in the ROI data for each advertising medium affect the optimal allocation. This analysis helps in understanding the robustness of the model.

## Dynamic Allocation with Reinvestment Strategy
The project explores a dynamic allocation strategy where half of the return is reinvested each month, adjusting the budget accordingly. This approach models a more realistic scenario where marketing budgets are not static.

## Stability Analysis
The stability of the monthly budget allocation is analyzed. The project discusses the variance in monthly spending per platform and proposes methods to achieve a more stable budget allocation over time.

## Implementation Details

### Python Code Usage
The Python notebook contains all the code and analyses for this project. It includes data loading, model formulation, solving, and result visualization.

### Code Structure and Key Functions
The notebook is structured to sequentially address each part of the project. Key functions include data preprocessing, model formulation, solver configuration, and result visualization.

## Results and Graphs
The project includes various graphs and visualizations that illustrate the optimal allocations, comparative analyses, and sensitivity studies. These visualizations aid in understanding the outcomes and implications of the analyses.

## Conclusion and Insights
The project provides valuable insights into how linear programming can be used to optimize marketing budgets. It highlights the importance of data-driven decision-making in marketing strategy development.

## Requirements and Dependencies
- Python 3.x
- Gurobi Optimizer
- Pandas, NumPy, Matplotlib (for data handling and visualization)

## How to Run the Code
1. Ensure all required libraries and Gurobi are installed.
2. Open the Jupyter notebook (`Project1.ipynb`).
3. Run the cells sequentially to replicate the analysis.

## Acknowledgements and References
This project is part of an academic assignment and is based on concepts from marketing analytics and mathematical optimization.

---
