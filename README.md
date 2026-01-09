# Machine Learning for Quantum State Tomography

This project implements a machine learning based pipeline to reconstruct the quantum state (density matrix) of an unknown single-qubit system from measurement data. The goal is to estimate the quantum state accurately using noisy experimental measurements.

##  Project Overview

Quantum State Tomography (QST) is the process of estimating the density matrix of a quantum system from measurement outcomes. Traditional methods scale poorly and are sensitive to noise. This project uses machine learning to improve reconstruction quality and robustness.

The pipeline performs:

- Generation of measurement data  
- Feature extraction from POVM / Pauli measurements  
- Machine learning based reconstruction  
- Validation against ground-truth quantum states  

---

##  Key Components

| Folder | Description |
|------|------------|
| `data/single_qubit/` | Measurement data and true quantum states |
| `notebooks/` | Jupyter notebook containing full ML pipeline |
| `outputs/` | Model predictions and validation metrics |
| `docs/` | Project documentation |
| `README.md` | Project overview |

---

## What the Model Does

The model learns a mapping from noisy measurement outcomes to the underlying quantum density matrix. It is trained on simulated quantum measurement data and evaluated using fidelity and reconstruction error.

The system is tested on multiple prepared quantum states to verify generalization.

---

## How to Run

1. Clone the repository  
```bash
git clone https://github.com/nikhilraj8371-svg/Machine-Learning-for-Quantum-Tomography.git
cd Machine-Learning-for-Quantum-Tomography



