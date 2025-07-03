# 🧮 Quantum Portfolio Optimization using QAOA

This project demonstrates how the **Quantum Approximate Optimization Algorithm (QAOA)** can be applied to **portfolio optimization** — a core problem in financial decision-making — using **Qiskit**.

> ⚡️ A hybrid quantum-classical approach for asset selection, risk balancing, and efficient portfolio construction.

---

## 📊 Problem Statement

In modern finance, constructing an optimal portfolio involves selecting a subset of assets to:

- Maximize **expected return**
- Minimize **risk** (variance of returns)
- Adhere to constraints like **budget** or **cardinality**

Classical solvers face scalability issues as asset count grows. QAOA, a variational quantum algorithm, offers a new paradigm for solving such **combinatorial optimization** problems by formulating them as **QUBOs (Quadratic Unconstrained Binary Optimization)**.

---

## 🧠 What This Project Does

✅ Models the portfolio using:
- Asset **expected returns** (`μ`)
- **Covariance matrix** of asset returns (`Σ`)
- Budget and risk factor

✅ Converts it into a `QuadraticProgram` via **Qiskit Optimization**

✅ Solves using QAOA with:
- `qiskit_algorithms.QAOA`
- `Sampler`-based backends (simulator or real)

✅ Visualizes selected assets, their returns, and the efficient frontier.

---

## 🚀 Technologies Used

- `Python 3.9`
- `Qiskit Terra (0.45.1)`
- `Qiskit Algorithms (0.3.1)`
- `Qiskit Optimization (0.6.1)`
- `Qiskit Finance (0.4.1)`
- `Matplotlib`, `NumPy`

---

## 📂 Repository Structure

| File/Folder                  | Description                                    |
|-----------------------------|------------------------------------------------|
| `quantum_portfolio.ipynb`   | Main notebook implementing QAOA for portfolio  |
| `README.md`                 | Project overview and instructions              |
| `requirements.txt`          | Python dependencies (Qiskit, etc.)             |
| `LICENSE`                   | MIT License file                               |

---

## ▶️ How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/kasinath-baiju/quantum-portfolio-optimization
   cd quantum-portfolio-optimization
