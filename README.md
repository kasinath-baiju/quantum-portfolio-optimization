# Quantum Portfolio Optimization using QAOA

This project demonstrates how Quantum Approximate Optimization Algorithm (QAOA) can be used to solve the classical financial portfolio optimization problem — a fundamental use case in quantum finance.

---

## 📊 Problem Statement

In finance, choosing the right combination of assets to maximize return while minimizing risk is critical. Classical algorithms often struggle with the **combinatorial complexity** as the number of assets increases.

This project formulates the **portfolio optimization problem** as a **Quadratic Unconstrained Binary Optimization (QUBO)** problem and solves it using QAOA with Qiskit.

---

## 🚀 Technologies Used

- [Python](https://www.python.org/)
- [Qiskit](https://qiskit.org/)
- [Qiskit Finance](https://qiskit-community.github.io/qiskit-finance/)
- [Qiskit Optimization](https://qiskit.org/documentation/optimization/)
- [Matplotlib](https://matplotlib.org/)

---

## 🧠 What This Project Does

- Models expected return and risk via a covariance matrix
- Constructs a binary optimization problem with constraints (e.g., budget)
- Uses Qiskit’s QAOA implementation to solve it
- Visualizes selected assets and portfolio efficiency

---

## 📁 Structure

| File                      | Description                                  |
|------ --------------------|----------------------------------------------|
| `quantum_portfolio.ipynb` | Main notebook containing QAOA implementation |
| `README.md`               | Project overview                             |
| `requirements.txt`        | Package list (optional)                      |

---

## 📷 Demo (Optional)

_Add screenshots or output graphs once the project is complete._

---

## 🧩 Future Work

- Compare QAOA with classical solvers
- Try different portfolio sizes
- Explore hardware backends (IBMQ)

---

## 📝 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
