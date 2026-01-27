# PHYS223: Quantum Computing Learning Journey

## Overview
This repository documents my progression through **PHYS223: Introduction to Quantum Computing** at the University of Victoria. Over the span of 3+ months (January 2025 - April 2025), I transformed from foundational quantum mechanics understanding to implementing production-grade quantum algorithms on IBM quantum hardware.

> Find my current Quantum Algorithms work in SENG447/CSC557 in [this repository](https://github.com/isaac-preyser/SENG457). 

---

## Chapter 1: Foundations (Early February 2025)
### Learning Phase: Quantum Mechanics → Circuit Implementation

**Key Commits:**
- `f82a9b7` - Set up environment configuration
- `e277b60` - Completed Assignment 3 (Bloch Sphere representation)

**What I learned:**
- **Mathematical Foundations**: Mastered Pauli matrix eigenvalues and eigenvectors, quantum state representation in Hilbert space
- **Quantum Visualization**: Implemented Bloch sphere visualization techniques to represent single-qubit states
- **Fundamentals**: Single-qubit gates (X, Y, Z, H), multi-qubit entanglement, and measurement basis concepts
    
**Evidence**: Assignment 2 & 3 notebooks contain detailed mathematical proofs and visualizations of quantum states on the Bloch sphere.

---

## Chapter 2: First Hardware Implementation (Mid-March 2025)
### Learning Phase: Simulator → Real Quantum Hardware

**Key Commits:**
- `dcb8a8b` - "implement BB84 protocol with Qiskit and add backend listing functionality" (March 18)
- `e277b60` - "Completed A3, still need to code in sketch on Bloch Sphere" (Feb 14)

**What I learned:**
- **Qiskit Mastery**: Built functional quantum circuits using Qiskit, learned to list and select IBM quantum backends
- **Quantum Cryptography**: Implemented BB84 quantum key distribution protocol from scratch
  - Encoded random bits using random bases (H or computational)
  - Performed sifting on measurement outcomes
  - Validated secure key generation using quantum properties
- **Real Hardware Exposure**: Accessed IBM Quantum devices and understood noise characteristics

**Code Quality Importance**: Added backend listing functionality, showing attention to usability and debugging

---

## Chapter 3: Iterative Problem-Solving on Hardware (Late March 2025)
### Learning Phase: Debugging Quantum Noise & Circuit Optimization

**Key Commits:**
- `bcc5523` - "Q3 done!" (March 20) - Error correction implementation
- `70e894d` - "initial work on Q4 done. not sure why there is so much noise on 8000 shots on quantum device. will need to ask in office hours." (March 20)
- `1bea928` - "No code changes made." (March 18) - *Reflecting on challenges*
- `0c2d55a` - "updated Q1 to actually use quantum computer rather than faking measurements via array copies" (March 27)
- `9f98702` - "add unitary to Q2 to ensure deterministic results" (March 27)
- `7e2ff20` - "add H gates to Q2 to get deterministic output" (March 27)

**What I learned:**
- **Quantum Error Analysis**: Analyzed real device noise and its effects on measurements (8000 shots analysis)
- **Circuit Debugging**: Systematically improved circuit design:
  - Added Hadamard gates for deterministic outputs
  - Implemented unitary operations to ensure quantum state control
  - Replaced classical array copying with real quantum measurements
- **Hardware vs Simulator Differences**: Deep understanding of noise characteristics, shot statistics, and fidelity
- **Iteration & Persistence**: Committed multiple times to same problems, showing methodical problem-solving

**Research Skills**: Identified issues, researched solutions, iterated until correct

---

## Chapter 4: Intermediate Quantum Algorithms (Late March - April 2025)
### Learning Phase: Complex Quantum Algorithms & Production Code

**Key Commits:**
- `3a12df8` - "update Q3" (March 27)
- `856d3b4` - "update Q3 discussion" (March 27)
- `103fbcb` - "fix Q2 F work" (March 28)
- `4c9b381` - "update Q5 description" (March 28)
- `4499ad9` - "a6 upload" (April 16)
- `e043591` - "finish q4" (April 16)

**Assignment 5 Content (982 lines)**: "Quantum algorithms with IBM-Q"
- **Algorithms Implemented**:
  - Grover's Algorithm: Quantum search optimization
  - Shor's Period-Finding Algorithm: Foundation for quantum cryptanalysis
  - Quantum Fourier Transform (QFT): Central to many quantum algorithms
  - Phase Estimation: Fundamental quantum algorithm
  - Simon's Algorithm: Quantum advantage demonstration

- **Hardware Integration**: 
  - Executed on real IBM quantum processors
  - Managed shot statistics (1000+)
  - Error correction protocols using 3-qubit bit-flip codes
  - Bloch sphere tomography with real hardware

**Assignment 6 Content**: Error mitigation and quantum state analysis
- Quantum state tomography
- Error correction evaluation
- Real device fidelity measurements


---


## Skill Progression Summary

### Programming & Framework Skills
| Skill | Level | Evidence |
|-------|-------|----------|
| Python | Intermediate | 40KB+ of notebook code across assignments |
| Qiskit | Intermediate | Full quantum algorithm implementations |
| NumPy | Intermediate | Linear algebra operations, state vectors |
| Jupyter/Python | Intermediate | Well-documented notebooks with visualizations |
| Git/GitHub | Intermediate | 50+ commits with clear messages |

### Quantum Computing Skills
| Skill | Level | Evidence |
|-------|-------|----------|
| Quantum Circuit Design | Intermediate | Multiple algorithm implementations |
| Real Hardware Execution | Intermediate | 8000+ shot real device measurements |
| Error Correction | Intermediate | 3-qubit bit-flip codes, fidelity analysis |
| Quantum Algorithms | Intermediate | Grover's, Shor's, Simon's, QFT, Phase Estimation |
| Quantum Cryptography | Intermediate | BB84 protocol implementation |
| State Tomography | Intermediate | Bloch sphere reconstruction from 1000+ shots |
| Noise Analysis | Intermediate | Real device characterization |

### Problem-Solving & Research
| Skill | Level | Evidence |
|-------|-------|----------|
| Debugging | Intermediate | 40KB+ of notebook code across assignments |
| Qiskit | Intermediate | Multiple quantum algorithm implementations |
| NumPy | Intermediate | Linear algebra operations, state vectors |
| Jupyter/IPython | Intermediate | Well-documented notebooks with visualizations |
| Git/GitHub | Intermediate | 50+ commits with clear messages |

### Quantum Computing Skills
| Skill | Level | Evidence |
|-------|-------|----------|
| Quantum Circuit Design | Intermediate | Multiple algorithm implementations |
| Real Hardware Execution | Intermediate | 8000+ shot real device measurements |
| Error Correction | Beginner-Intermediate | 3-qubit bit-flip codes, fidelity analysis |
| Quantum Algorithms | Intermediate | Grover's, Shor's, Simon's, QFT, Phase Estimation |
| Quantum Cryptography | Intermediate | BB84 protocol implementation |
| State Tomography | Intermediate | Bloch sphere reconstruction from 1000+ shots |
| Noise Analysis | Beginner-Intermediate | Real device characterization |

### Problem-Solving & Research
| Skill | Level | Evidence |
|-------|-------|----------|
| Debugging | Intermediate | Iterated Q1-Q5 until hardware validation |
| Hardware Troubleshooting | Intermediate | Noise analysis, deterministic output design |
| Theoretical Understanding | Intermediate | Detailed mathematical proofs in assignments |

- Implemented 3-qubit bit-flip error correction codes
- Measured computational basis probabilities for correction fidelity
- Understood device noise impact on quantum state preservation
- Debugged and optimized circuits for real hardware constraints

### ✅ Quantum Information Processing
- Quantum state tomography using projection measurements
- Bloch sphere visualization and analysis
- Eigenvalue/eigenvector decomposition of Pauli matrices
- Multi-qubit entanglement and measurement

---

## Repository Statistics

- **Total Commits**: 50+
- **Assignments Completed**: 6 (A2, A3, A5, A6, Final)
- **Notebooks**: 10+ Jupyter notebooks
- **Timeline**: January 2025 - January 2026
- **Progression**: Novice → Intermediate practitioner

---
