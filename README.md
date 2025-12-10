# Clinic Optimization and Workflow Simulation
**Northwestern MSDS 460 — Decision Analytics | Final Project**

##  Project Overview
This project implements a multi-stage optimization and simulation model for a Tokyo dermatology clinic. The goal was to improve patient-flow efficiency, resource utilization, and overall operational cost.

The analysis integrates **deterministic optimization** (Linear Programming) and **stochastic queueing simulation** (SimPy) to evaluate staffing and workflow configurations.

##  Objectives
- Minimize patient waiting time while maintaining realistic utilization.
- Identify optimal staffing levels for Weekdays vs. Saturdays.
- Quantify trade-offs between service cost and patient experience.
- Test a **Hybrid Reservation Workflow** redesign.

##  Methodology
1. **LP Baseline (PuLP):** Deterministic model to balance patient inflow and doctor capacity.
2. **Queueing Simulation (SimPy):** Discrete-event simulation modeling stochastic arrivals and service times.
3. **Sensitivity Analysis:** Cost modeling integrating staff, fixed, and waiting costs.

##  Technologies Used
- **Python**
- **SimPy** (Discrete-Event Simulation)
- **PuLP** (Linear Programming)
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib** (Visualization)

##  File Structure
- `notebooks/`: Contains the main Python analysis and simulation code.
- `data/`: The arrival data generated for the simulation.
- `reports/`: Full project report and presentation slides.
