# Coupled Pendulum Dynamics using RK4

Numerical simulation of two coupled pendulums, built from the Lagrangian equations of motion, using a custom fourth order Runge Kutta (RK4) integrator.

## Overview
The simulation models beating, damping, and driven resonance behavior in a coupled pendulum system, and validates the integrator's accuracy through convergence and energy conservation tests.

## Tools & Libraries
Python, NumPy, Matplotlib, SciPy

## Project Workflow
1. Derived the coupled equations of motion from the Lagrangian
2. Built a custom RK4 integrator from scratch
3. Simulated undamped beating, damped oscillations, and driven resonance
4. Verified numerical accuracy through a convergence order test
5. Verified energy conservation for the undamped case
6. Animated the pendulum motion

## Results
Convergence order: 3.97 (theoretical RK4 order is 4)
Relative energy drift: 6.5e-09

These results confirm the integrator behaves as a true fourth order method and conserves energy to near machine precision in the undamped case.

## Files
coupled_pendulum_rk4.ipynb contains the full simulation, validation tests, and plots.

## How to Run
1. Clone this repository
2. Install requirements: pip install numpy matplotlib scipy
3. Open coupled_pendulum_rk4.ipynb in Jupyter Notebook and run all cells
