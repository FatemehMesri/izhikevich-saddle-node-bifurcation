# izhikevich-saddle-node-bifurcation
Computational analysis of the saddle-node bifurcation in the Izhikevich neuron model (Regular Spiking)
# Saddle-Node Bifurcation in the Izhikevich Neuron Model

Computational analysis of the saddle-node bifurcation in the Izhikevich Regular Spiking (RS) neuron model.

## Overview
This repository contains a detailed numerical investigation of the saddle-node bifurcation in the Izhikevich model, including:

- Number of equilibrium points vs. injected current
- Discriminant analysis
- Bifurcation diagram of stable and unstable equilibria
- Phase-space trajectories and nullclines near the bifurcation point

## Model
The Izhikevich neuron model (Regular Spiking parameters) is used:

\[
\begin{aligned}
\dot{v} &= 0.04v^2 + 5v + 140 - u + I \\
\dot{u} &= a(bv - u)
\end{aligned}
\]

with reset condition when \( v \geq 30 \) mV.

## Contents
- `final.ipynb` — Complete analysis notebook with figures

## Requirements
- Python 3
- NumPy
- Matplotlib
- (Optional) PyTorch

## Author
Fatemeh Mesri  
Physics Graduate | Computational Neuroscience  
K. N. Toosi University of Technology
