# 1D Heat Conduction Simulation 🔥

This project simulates **1D transient heat conduction** using numerical methods.  
It is intended for learning, experimentation, and validation of numerical schemes.

Equation solved:
\begin{equation}
\frac{\partial T}{\partial t} = \alpha \frac{\partial^2 T}{\partial x^2}
\end{equation}

Where:
- \(T(x,t)\): Temperature distribution
- \(\alpha = \frac{k}{\rho c_p}\): Thermal diffusivity

---
## 📂 Repository Structure

1D-Heat-Conduction/

├── README.md # Project overview

├── docs/ # Documentation

├── src/ # Source code

├── examples/ # Simulation cases

├── tests/ # Unit tests

└── notebooks/ # Jupyter notebooks

---

## 🚀 How to Use
Run a simulation (example):
```bash
python src/main.py
