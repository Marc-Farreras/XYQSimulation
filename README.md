# **XYQSimulation**

This repository contains the code used in the research work *"Simulation of the 1D XY Model on a Quantum Computer"* ([arXiv:2410.21143](https://arxiv.org/abs/2410.21143)).

## **Abstract**
The field of quantum computing has grown fast in recent years, both in theoretical advancements and the practical construction of quantum computers. These computers were initially proposed, among other reasons, to efficiently simulate and comprehend the complexities of quantum physics. In this paper, we present the comprehensive scheme for the exact simulation of the 1-D XY model on a quantum computer. We successfully diagonalize the proposed Hamiltonian, enabling access to the complete energy spectrum. Furthermore, we propose a novel approach to design a quantum circuit to perform exact time evolution. Among all the possibilities this opens, we compute the ground and excited state energies for the symmetric XY model with spin chains of n = 4 and n = 8 spins. Further, we calculate the expected value of transverse magnetization for the ground state in the transverse Ising model. Both studies allow the observation of a quantum phase transition from an antiferromagnetic to a paramagnetic state. Additionally, we have simulated the time evolution of the state all spins up in the transverse Ising model. The scalability and high performance of our algorithm make it an ideal candidate for benchmarking purposes, while also laying the foundation for simulating other integrable models on quantum computers.

---

## **Repository Content**
The repository is organized into the following folders and files:

### **1. `XY_library_qibo`**
This folder contains five Jupyter notebooks:

- **`XY_cqirc_class.ipynb`**:
  - Defines the classes for creating the fermionic Fourier Transform circuit and the circuit that diagonalizes the 1D XY model Hamiltonian.
  
- **`Energy_4qubits_g0.ipynb`** and **`Energy_8qubits_g0.ipynb`**:
  - Use the proposed circuit to compute the ground and first excited state energies of the 1D XY model with anisotropy parameter \( g = 0 \), for systems of \( n = 4 \) and \( n = 8 \) qubits, respectively.

- **`Magnetization_4qubits_g1.ipynb`**:
  - Explores the quantum phase transition in the 1D XY model for a system of \( n = 4 \) qubits, using the proposed circuit.

- **`Time_evolution_4qubits_g1.ipynb`**:
  - Simulates the time evolution of the transverse magnetization for a system of \( n = 4 \) qubits using the proposed circuit.

### **2. `Bachelor_thesis`**
This folder contains the code from the Bachelor's thesis titled [*"Simulation of the XY Model on a Quantum Computer"*](https://diposit.ub.edu/dspace/handle/2445/201015), submitted to the University of Barcelona. The thesis was awarded the **2023 Research Prize for Students** by the REAL SOCIEDAD ESPAÑOLA (GEFES). The work awarded can be found [here](https://gefes-rsef.org/premios-de-investigacion-para-estudiantes-2023-marc-farreras-bartra/).




