
# 🧠 Quantum Computing Simulation Project

This project simulates the foundational concepts of quantum computing using Python, Qiskit, and Jupyter Notebook. It covers qubits, quantum gates, quantum circuits, and Deutsch-Jozsa algorithm.

---

## 📁 Project Structure

```
quantum-computing-simulation/
├── quantum_simulation.ipynb     # Main Jupyter notebook with all code
├── environment.yml              # Conda environment for reproducibility
└── README.md                    # Project overview and instructions
```

---

## ⚙️ Setup Instructions

### 📌 1. Clone the Repository

```bash
gh repo clone rakibul181/Simulating-Foundational-Quantum-Computing-Concepts
cd src
```

### 🐍 2. Create Conda Environment

If you're using **Miniconda**:

```bash
conda env create -f environment.yml
conda activate quantum-env
```

> `quantum-env` is the environment name defined in `environment.yml`.

---

### 📓 3. Launch the Notebook

```bash
jupyter notebook quantum_simulation.ipynb
```

---

## 📚 Topics Covered

- Qubits and State Vectors
- Superposition and Entanglement
- Quantum Gates (X, Y, Z, H, CNOT, etc.)
- Quantum Circuits
- State Evolution and Measurement
- Deutsch-Jozsa Algorithm
- Visualization (Bloch Sphere, Histogram)

---

## 🧪 Requirements

All dependencies are listed in `environment.yml`. Major packages include:

- `qiskit`
- `jupyter`
- `matplotlib`
- `numpy`
- `scipy`

---

## 🚀 Output & Visualizations

- Quantum statevectors and measurement probabilities
- Circuit diagrams and gate simulation
- Histograms and Bloch sphere visualizations

---

## 📜 License

This project is for educational and academic purposes.

---

## 🤝 Acknowledgements

- [Qiskit Textbook](https://qiskit.org/textbook/)
- IBM Quantum Experience
