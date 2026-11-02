# Numerical Optimization

A collection of implementations and experiments in Numerical Optimization, with an emphasis on understanding the mathematical foundations behind optimization algorithms and their computational behaviour.

## About the Project

This repository is a personal learning and implementation project inspired by two courses:

Linear Algebra, Numerical and Complex Analysis — Indian Institute of Technology Kharagpur

Applied Computational Methods — Indian Institute of Technology Kharagpur

Rather than relying entirely on existing optimization libraries, I have focused on understanding the underlying mathematics, computational procedures, and numerical considerations involved in each method.

## What is in this Repository?
Implementation of matrices and relevant methods such as finding the determinant and normalization.

### Numerical optimization methods:

#### Direct methods:
1. Gauss' Elimination Method
2. Crammer's Rule

#### Iterative methods:
1. Jacobi Method
2. Gauss-Seidel Method


## Getting Started

### Prerequisites

- Python 3.10+
- pip

### Installation

Clone the repository:

```bash
git clone https://github.com/<username>/Numerical-Optimization.git
cd Numerical-Optimization

Create and activate a virtual environment:

python -m venv .venv
```

On Windows:

```bash
.venv\Scripts\Activate.ps1
```

Install the required dependencies for a particular module:
```bash
pip install -r matrix/requirements.txt
```
Running an Implementation

For example, to run the matrix implementation:
```bash
cd matrix
python main.py
```

### Future Work

Expand the linear algebra module.

Implement fundamental unconstrained optimization algorithms.

Explore constrained optimization techniques.

Study convergence behaviour through numerical experiments.

Benchmark implementations against established scientific computing libraries.

Add mathematical derivations and documentation for individual algorithms.

### Acknowledgements

<it>This project draws inspiration from the coursework and learning materials of two courses mentioned</it>.