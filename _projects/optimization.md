---
title: "Large-Scale Vehicle Routing Optimization"
excerpt: "Developing a hybrid metaheuristic for a multi-depot vehicle routing problem with time windows."
collection: projects
tags:
  - Optimization
  - Logistics
  - Python
  - Operations Research
header:
  teaser: /assets/images/optimization-teaser.jpg
---

## Problem Context
A major logistics company faced inefficiencies in their last-mile delivery network, leading to high fuel costs and delayed deliveries. The existing manual planning process was unable to handle the complexity of 500+ daily orders across multiple depots.

## Objective
To minimize total transportation costs (fuel + driver wages) while adhering to strict time windows and vehicle capacity constraints.

## Data Description
The dataset included:
*   Geospatial data for 5 depots and 1000+ customer locations.
*   Historical traffic data for travel time estimation.
*   Vehicle fleet specifications (capacity, fuel consumption).
*   Order details (weight, volume, delivery time window).

## Methodology
1.  **Mathematical Modeling:** Formulated the problem as a Mixed-Integer Linear Programming (MILP) model.
2.  **Algorithm Design:** Developed a hybrid algorithm combining a Genetic Algorithm (GA) for global search with Variable Neighborhood Search (VNS) for local refinement.
3.  **Implementation:** Implemented the solution in Python using custom classes and verified against small instances using Gurobi.

## Tools and Technologies
*   **Languages:** Python (NumPy, Pandas)
*   **Optimization Solvers:** Gurobi (for benchmarking)
*   **Geospatial Analysis:** Folium, OSRM

## Results
*   **Cost Reduction:** Achieved a **15% reduction** in total transportation costs compared to the previous baseline.
*   **Efficiency:** Reduced planning time from 4 hours to 15 minutes.
*   **Service Level:** Improved on-time delivery rate from 85% to 98%.

## Impact
The solution was deployed into the company's TMS, directly impacting daily operations and strategic fleet sizing decisions.

[<i class="fab fa-github"></i> View on GitHub](https://github.com/leogasis/project-repo)
