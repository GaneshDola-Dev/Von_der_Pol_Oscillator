# Von_der_Pol_Oscillator
MATLAB analysis of Van der Pol oscillator with solver comparisons and error analysis

# Van der Pol Oscillator Analysis

This project presents a MATLAB-based analysis of the Van der Pol oscillator — a nonlinear second-order differential equation modeling electrical circuits with vacuum tubes.

## 🔍 Motivation
The Van der Pol oscillator exhibits both stiff and non-stiff behavior depending on the damping parameter `μ`. This project explores solver performance and error behavior across regimes.

## 📊 Features
- Vector field and phase portrait visualization
- Solver comparison: `ode45`, `ode23s`, `ode15s`, Euler methods
- Absolute and relative error analysis
- Modular helper functions for reuse

## 🧪 Methods
- Non-stiff case: `μ = 1` solved with `ode45`
- Stiff case: `μ = 1000` solved with `ode15s`
- Euler explicit/implicit methods benchmarked
- Error metrics computed against high-accuracy reference solution

## 📁 Files
- `Van_der_Pol_Oscillator.pdf` – Presentation slides
- `main.m` – Entry script
- `vdpODE.m`, `plotVectorField.m`, etc. – Modular helper functions

## 🚀 How to Run
Open MATLAB and run `main.m`. All the helper functions are in the same folder.

## 📌 Future Work
- Extend to chaotic systems (e.g., Duffing oscillator)
- Add interactive GUI for parameter tuning
- Port to Python using SciPy for broader accessibility
