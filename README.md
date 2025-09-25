# DAA_Project1_g28705598

This project is part of my Design and Analysis of Algorithms (DAA) course.  
It analyzes the runtime of a nested loop program and compares it with the theoretical complexity O((log log n)^2).

This repository contains the code and report for analyzing a nested-loop algorithm with runtime $(\log\log n)^2$. It implements the assignment’s exact updates—outer loop $j \leftarrow 1.2j$, inner loop $k \leftarrow k^{1.5}$—and includes a small harness to measure median runtimes across input sizes, scale theory with a single factor $\alpha$, and plot measured vs. predicted performance. Run `python run_experiments.py` to reproduce the tables and figure.


---

## Files
- `DAA_Project1_g28705598.ipynb` → Jupyter Notebook with code, outputs, and plots.
- `README.md` → Instructions and project details.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yaseenjunaid657/DAA_Project1_g28705598.git
   cd DAA_Project1_g28705598

2. Install dependencies (if not already installed):
   ```bash
    pip install matplotlib numpy

