# 🧑‍💻 Quantum Computing Notebooks

A collection of interactive Jupyter notebooks exploring **quantum computing concepts** using [Qiskit](https://qiskit.org/).  
This repository serves as both my learning journey and a portfolio of quantum experiments — from **superposition** to **entanglement** and beyond.

---

## 📘 Contents

### 1. Basic Quantum Gates
📂 `BasicQuantumGates.ipynb`  
Introduces fundamental quantum gates (X, Y, Z, Hadamard, etc.) and their effects on qubits.  
Includes circuit examples and visualizations.

### 2. Bell State & Entanglement
📂 `BellStates_Entanglement.ipynb`  
Builds all four **Bell states (Φ⁺, Φ⁻, Ψ⁺, Ψ⁻)** using Qiskit.  
Explains how entanglement works, shows measurement correlations, and visualizes results with histograms.

### 3. Bernstein Vazirani Algorithm
📂 `BernsteinVazirani.ipynb`  
Implements the Bernstein-Vazirani algorithm to efficiently determine a hidden bit string using quantum parallelism.

### 4. Deutsch Jozsa Algorithm (1 Qubit)
📂 `DeutschJozsa_1Qubit.ipynb`  
Demonstrates the Deutsch-Jozsa algorithm for a single qubit case, distinguishing between constant and balanced functions.

### 5. Deutsch Jozsa Algorithm (multi Qubits)
📂 `DeutschJozsa_MultiQubits.ipynb`  
Extends the Deutsch-Jozsa algorithm to multiple qubits, showing exponential speedup over classical approaches.

### 6. Classical Gates Using Quantum Gates
📂 `Classical_Gates_Using_Quantum_Gates.ipynb`  
Implements classical logic gates (NOT, AND, OR, XOR) using quantum circuits.  
Simulates the gates on a quantum backend and visualizes the results.

### 7. Run on IBM Fake Hardware
📂 `Run_On_IBM_Fake_Hardware.ipynb`  
Simulates quantum circuits on IBM's fake hardware backend. Demonstrates how to use Qiskit's fake backends for testing and debugging quantum algorithms.

### 8. Run on IBM Quantum Hardware
📂 `Run_On_IBM_Quantum_Hardware.ipynb`  
Executes quantum circuits on real IBM quantum hardware. Includes steps for transpiling circuits, submitting jobs, and analyzing results from IBM's quantum devices.

---

## 🚀 How to Run

Clone the repo:

```bash
git clone https://github.com/mr-mohitrawat/quantum-computing-notebooks.git
cd quantum-computing-notebooks
```

Install dependencies:
```bash
pip install qiskit matplotlib
```

Run notebooks:
```bash
jupyter notebook
```



## 👤 Author

**Mohit Rawat**  
💼 Software Engineer | Aspiring Quantum Computing Researcher  
🌐 [LinkedIn](https://www.linkedin.com/in/mr-mohitrawat/)  
🧑‍💻 Exploring the intersection of **Quantum Computing, AI, and Physics**
