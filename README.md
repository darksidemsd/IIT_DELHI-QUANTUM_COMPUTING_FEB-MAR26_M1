# IIT Delhi Quantum Computing Workshop  
## Single-Qubit Foundations & Quantum State Analysis  

**Participant:** Sumit Dey Sarkar  
**Platform:** Python 3.x + Qiskit  
**Workshop:** IIT Delhi – Quantum Computing  

---

## Overview

This repository contains a complete technical implementation of six core quantum computing experiments conducted during the IIT Delhi Quantum Computing Workshop.  

The project rigorously explores single-qubit systems from geometric, algebraic, and statistical perspectives using Qiskit’s statevector formalism.

The experiments validate the mathematical structure of SU(2) operations, Bloch sphere geometry, quantum measurement statistics, phase behavior, and quantum state tomography.

---

## Experiments Included

### 1. State Preparation & Bloch Sphere Representation
- Construction of canonical basis and superposition states
- Computation of amplitudes, probabilities, Bloch angles (θ, ϕ)
- Extraction of Bloch vector via Pauli expectation values
- Verification of pole vs equatorial mapping

---

### 2. Single-Qubit Gates as Rotations
- Implementation of X, Y, Z, H, Rx, Ry, Rz gates
- SU(2) rotational interpretation
- Additivity of same-axis rotations
- Demonstration of non-commutativity

---

### 3. Measurement & Statistical Sampling
- Binomial modeling of measurement outcomes
- Clopper–Pearson confidence intervals
- Empirical verification of 1/√N convergence law
- Coverage rate analysis

---

### 4. Additivity & Rotational Algebra
- Validation of rotation composition
- Bloch trajectory comparison
- Operator ordering effects

---

### 5. Global vs Relative Phase
- Separation of global and physically observable phase
- Longitude shifts on Bloch sphere
- Interference behavior analysis

---

### 6. Quantum State Tomography
- Reconstruction using ⟨σx⟩, ⟨σy⟩, ⟨σz⟩
- Density matrix formulation
- Fidelity computation
- Shot-dependent error scaling

---

## Technical Stack

- Python 3.x
- NumPy
- SciPy
- Matplotlib
- Qiskit (Statevector Simulation)

All simulations were executed in a controlled virtual Python environment to ensure reproducibility and isolation from system dependencies.

---

## Mathematical Foundations

The repository implements:

- Bloch sphere parameterization  
- SU(2) unitary rotations  
- Pauli operator expectation values  
- Binomial sampling theory  
- Confidence interval estimation  
- Quantum state fidelity metrics  

---

## Key Outcomes

- Verified geometric representation of qubit states  
- Demonstrated non-abelian structure of quantum rotations  
- Confirmed statistical convergence of measurement  
- Validated tomography reconstruction accuracy  

---

## Reproducibility

To run locally:

```bash
python3 -m venv venv
source venv/bin/activate
pip install qiskit numpy scipy matplotlib notebook
jupyter notebook
