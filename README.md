# Qubit State Explorer

A simple quantum computing project built using **Python** and **Qiskit** to explore how different quantum gates affect the state of a single qubit.

---

## 📖 Project Overview

This project was developed as part of the **Session 2 Coding Assignment**. It demonstrates the behavior of a single qubit by allowing the user to apply different quantum gates and observe the resulting quantum state.

The program generates:

- Quantum Circuit
- Bloch Sphere Visualization
- Measurement Probabilities of |0⟩ and |1⟩

---

## 🎯 Objective

The objective of this project is to understand the effect of fundamental quantum gates on a single qubit and visualize the resulting quantum state using Qiskit.

---

## ⚙️ Features

- Interactive gate selection
- Supports the following quantum gates:
  - X Gate
  - Y Gate
  - Z Gate
  - Hadamard (H) Gate
  - RY Rotation Gate
- User-defined rotation angle for the RY gate
- Displays the generated quantum circuit
- Visualizes the qubit state using the Bloch Sphere
- Calculates the probabilities of measuring:
  - |0⟩
  - |1⟩

---

## 🛠️ Technologies Used

- Python
- Qiskit
- NumPy
- Matplotlib
- Google Colab

---

## 📂 Project Structure

```
Qubit-State-Explorer/
│
├── Session2_Qubit_State_Explorer.ipynb
├── README.md
├── Report.pdf
└── screenshots/
    ├── Screenshot (347).png
    ├── Screenshot (348).png
    ├── Screenshot (349).png
    ├── Screenshot (350).png
    └── Screenshot (351).png
```

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/YourUsername/Qubit-State-Explorer.git
```

2. Open the notebook in **Google Colab** or **Jupyter Notebook**.

3. Install the required libraries.

```bash
pip install qiskit qiskit-aer pylatexenc
```

4. Run all notebook cells.

5. Select any quantum gate from the menu.

6. If the **RY Gate** is selected, enter the desired rotation angle in radians.

7. View the generated quantum circuit, Bloch Sphere, and measurement probabilities.

---

## 📊 Sample Results

The project successfully demonstrates the effect of different quantum gates on a single qubit.

Some observed results include:

| Gate | Probability of \|0⟩ | Probability of \|1⟩ |
|------|--------------------:|--------------------:|
| X | 0.0 | 1.0 |
| Y | 0.0 | 1.0 |
| Z | 1.0 | 0.0 |
| H | 0.5 | 0.5 |
| RY (θ = 1.05 rad) | 0.763 | 0.237 |

---

## 📷 Output Screenshots

The repository contains screenshots demonstrating:

- Quantum Circuits
- Bloch Sphere Visualizations
- Measurement Probabilities

for all implemented quantum gates.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Basics of quantum circuits
- Single-qubit gate operations
- Statevector representation
- Bloch Sphere visualization
- Quantum measurement probabilities
- Using Qiskit for quantum circuit simulation

---

## 📄 Report

A detailed project report explaining the implementation, methodology, observations, and results is included in this repository as **Report.pdf**.

---

## 👨‍💻 Author

**Aditya Singhal**

B.Tech Artificial Intelligence & Machine Learning

---

## 📜 License

This project is developed for educational purposes as part of the **QuantumX Session 2 Coding Assignment**.
