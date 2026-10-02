Operations Research & MILP Optimization
Overview
This repository contains Mixed Integer Linear Programming (MILP) models developed in Python to solve complex decision-making and resource allocation problems. The mathematical models are implemented and solved using the PuLP library.

Projects Included
1. Hospital Staffing & Shift Scheduling
Objective: Minimize total weekly staffing costs in an emergency department while adhering to strict labor regulations and minimum coverage requirements.

Constraints Handled: Mandatory rest periods (e.g., minimum 16h rest after night shifts), maximum weekly workloads, skill/specialty requirements per shift, and dynamic unavailability matrices.

Output: An optimal, automated weekly shift schedule generation for the nursing staff.

2. Network Restoration & Routing Optimization
Objective: Minimize the total cost of unsatisfied demand, repair operations, and temporary link usage in a damaged communication network.

Constraints Handled: Flow conservation, physical and temporary link capacities, repair crew scheduling (avoiding overlapping tasks), and time-dependent link availability based on repair completion.
Output: Optimal flow routing for critical nodes and an efficient repair schedule over a multi-period time horizon.

Technologies Used:
a) Python
b) PuLP (Linear Programming API)
c) Jupyter Notebook
