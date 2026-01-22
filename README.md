# 2D Ising Model Simulation

<div align="center">
  <img src="ising_model.gif" width="600" />
  <p><em>Real-time visualization of ferromagnetic domain formation near the critical temperature.</em></p>
</div>

## Overview
This project is a Python-based Monte Carlo simulation of the 2D Ising Model, a mathematical model of ferromagnetism in statistical mechanics. It uses the **Metropolis-Hastings algorithm** to simulate magnetic spin dynamics on a lattice.

I built this to explore phase transitions, specifically how macroscopic order (magnetism) emerges from microscopic interactions and how systems behave near the critical point.

## Features
* **Metropolis Dynamics:** Implements the Metropolis-Hastings acceptance criterion for spin flips.
* **Real-time Visualization:** Uses `matplotlib.animation` to visualize spin evolution and domain growth.
* **Periodic Boundary Conditions:** Simulates an infinite lattice by wrapping grid edges.
* **Customizable Parameters:** Easy adjustment of Grid Size ($N$), Temperature ($T$), and Interaction Strength ($J$).

## Usage

### 1. Prerequisites
You will need Python installed along with the following libraries:
```bash
pip install numpy matplotlib
