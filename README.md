# Numerical Methods in Python – Notebook Collection

This repository contains three Jupyter Notebooks translated from MATLAB to Python. These notebooks are part of the coursework materials aimed at illustrating key numerical methods and their implementation in Python. Each notebook is designed to support learning with annotated code and visual outputs.

## Contents

### 1. `binary64_numerical_errors.ipynb`

**Topic**: Floating-Point Arithmetic and Numerical Errors  
**Description**:  
This notebook explores how real numbers are represented in computer memory using the IEEE 754 double-precision format (`binary64`). It illustrates how rounding errors, finite precision, and cancellation can affect numerical results in computations.

**Key Concepts**:
- Floating-point representation  
- Machine epsilon (`eps`)  
- Round-off and cancellation errors  
- Visualisation of numerical inaccuracy in iterative calculations  

**Learning Outcome**:  
Understand the source and behaviour of numerical errors in scientific computing.

---

### 2. `Euler_ODE.ipynb`

**Topic**: Solving Ordinary Differential Equations Using Euler’s Method  
**Description**:  
This notebook demonstrates the use of the forward Euler method to numerically solve first-order ordinary differential equations (ODEs). It compares the numerical solution with the exact analytical solution to highlight the error accumulation over time.

**Key Concepts**:
- First-order ODEs  
- Forward Euler method  
- Discretisation and time steps  
- Error analysis: absolute and relative errors  

**Learning Outcome**:  
Gain practical experience implementing numerical solvers for ODEs and evaluating their accuracy.

---

### 3. `proj_Euler.ipynb`

**Topic**: Motion of a Projectile with and without Air Resistance  
**Description**:  
This notebook applies the Euler method to a real-world physics problem: simulating the motion of a projectile under gravity, both with and without air resistance. It includes 2D motion and provides visual plots for position and velocity over time.

**Key Concepts**:
- Newton’s second law in 2D  
- Euler integration in multiple dimensions  
- Modelling air resistance (linear and quadratic)  
- Trajectory plotting and analysis  

**Learning Outcome**:  
Model and analyse real-world physical systems using numerical methods.
