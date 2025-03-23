# Quantum Error Correction Library

This repository contains implementations and experiments on quantum error correction codes, specifically for phase-bit flip error correction using Qiskit.

## Overview

This repository hosts Jupyter notebooks that demonstrate quantum error correction techniques using Qiskit. Each notebook walks through the process of state preparation, encoding, error simulation, syndrome detection, correction, and decoding:
- The **9 Qubit Phase and Bit Flip Error Correction** notebook shows a combined approach for correcting both phase and bit flip errors with redundant encoding.
- The **3 Qubit Bit Flip Error Correction** notebook focuses on correcting single bit flip errors using a minimal qubit scheme.
- The **3 Qubit Phase Flip Error Correction** notebook details the method for detecting and correcting phase errors in a compact setup.

## Getting Started

1. Install Qiskit:
   ```
   pip install qiskit
   ```
2. Open the provided notebooks using Jupyter Notebook or JupyterLab.
3. Execute the cells in order to simulate quantum error correction.

## Repository Structure

- **9qubit-PhaseBit-flip-Error-correction copy.ipynb**  
  Notebook demonstrating 9-qubit phase and bit flip error correction.
- **3qubit-Bit-flip-Error-correction.ipynb**  
  Notebook for 3-qubit bit flip error correction.
- **3qubit-phase-flip-Error-correction.ipynb**  
  Notebook for 3-qubit phase flip error correction.
- **README.md**  
  This file.

## License

Distributed under the MIT License.
