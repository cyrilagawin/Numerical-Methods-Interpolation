# Linear Algebra Applications: Interpolation 📈

This repository contains the Python implementation and the official laboratory report for **Emath 211: Numerical Method**. The project demonstrates how to apply various polynomial interpolation techniques to solve real-world engineering problems across different disciplines.

## 🚀 Project Overview

The core objective of this laboratory is to translate discrete physical data points into continuous mathematical models. By setting up and solving systems of linear equations ($Ax = b$), the code fits quadratic and cubic polynomials to data, allowing for accurate estimations, root-finding, and derivative extraction.

### Engineering Problems Solved:
1. **Civil Engineering (Bridge Deformation):** Estimated the vertical deflection of a bridge beam using quadratic interpolation.
2. **Mechanical Engineering (Thermodynamics):** Modeled the non-linear relationship between lubricant viscosity and temperature, comparing exact quadratic fit to linear interpolation.
3. **Aerospace Engineering (Flight Path):** Reconstructed a drone's steady climb using a cubic polynomial and utilized its first derivative to estimate vertical velocity.
4. **Electrical Engineering (Signal Processing):** Interpolated discrete digital-to-analog converter (DAC) voltage samples using **Lagrange Interpolation** and discussed the limitations of Runge's Phenomenon.
5. **Chemical Engineering (Reaction Rates):** Predicted reactant concentration decay, solved for specific concentration roots, and demonstrated the dangers of polynomial extrapolation compared to least squares linear fitting.

## 📁 Repository Contents

* `interpolation_lab.py` / `Interpolation_Lab.ipynb`: The core Python scripts containing the mathematical formulations, matrix setups, and computational solvers for all five problems.
* `Lab_Report.pdf`: The detailed engineering documentation containing problem statements, formatted mathematical matrices, result analysis, and discussion of interpolation limitations.

## 🛠️ Technologies & Libraries Used

* **Python 3**
* **NumPy:** Used for array manipulation and direct linear algebra solving (`np.linalg.solve`, `np.roots`, `np.polyfit`).
* **SciPy:** Used specifically for the `lagrange` interpolation function.
* **Plotly:** Used to generate interactive, web-based data visualizations (Scroll-to-zoom and click-to-pan).

## ⚙️ How to Run

1. Ensure you have Python installed along with the required libraries. You can install the dependencies using pip:
   ```bash
   pip install numpy scipy plotly
