# Numerical Methods in Python – Notebook Collection

This repository contains three Jupyter Notebooks translated from MATLAB to Python. These notebooks are part of the coursework materials aimed at illustrating key numerical methods and their implementation in Python. Each notebook is designed to support learning with annotated code and visual outputs.

## Week 1 Contents

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





## Week 2 Contents

### 1. `float64-vs-float32.ipynb`

Topic: Memory Efficiency and Floating-Point Representation
Description:
This notebook compares the memory usage and structure of float64 and float32 arrays in NumPy. It includes explanations of IEEE 754 representation and shows how different float precisions impact memory consumption and numerical fidelity.

Key Concepts:
	•	IEEE 754 binary structure of floating-point numbers
	•	Memory layout in NumPy arrays
	•	tobytes() and frombuffer() for binary inspection
	•	Memory usage comparison between data types

Learning Outcome:
Understand how float precision affects memory usage and how floating-point numbers are stored in computer memory.

⸻

### 2. `numpy-vs-pytnon-structure.ipynb`

Topic: Python Lists vs. NumPy Arrays – Memory Structure and Efficiency
Description:
This notebook compares Python native lists with NumPy arrays in terms of internal memory layout, type uniformity, and performance. It also visualises memory usage and discusses why NumPy is more efficient for numerical computing.

Key Concepts:
	•	Object references in Python lists
	•	Contiguous memory in NumPy arrays
	•	Internal memory strides and data alignment
	•	Visualisation of memory usage using bar plots

Learning Outcome:
Identify how NumPy optimises memory and understand the underlying differences between high-level and low-level array structures.

⸻

### 3. `kepler_dynamics.ipynb`

Topic: Kepler’s Laws and Orbital Dynamics Using Numerical Integration
Description:
This notebook numerically solves Kepler’s problem using classical integration schemes. It explores the motion of a body under a central force and provides insights into orbital dynamics with varying initial conditions.

Key Concepts:
	•	Newtonian gravity and two-body problem
	•	Implementation of numerical integration for orbital motion
	•	Conservation of angular momentum and energy
	•	Analysis of elliptic and circular orbits

Learning Outcome:
Simulate celestial mechanics and study the dynamics of planetary motion using numerical solvers.

⸻

### 4. `Kepler_verlet.ipynb`

Topic: Verlet Integration for Orbital Motion
Description:
Building on the Kepler dynamics notebook, this one applies the Verlet method to improve numerical stability and energy conservation in orbital simulations. It is particularly suited for long-term integration of conservative systems.

Key Concepts:
	•	Verlet algorithm for second-order ODEs
	•	Stability in time integration
	•	Phase-space trajectory analysis
	•	Comparison with Euler and Runge-Kutta methods

Learning Outcome:
Apply the Verlet method to simulate planetary orbits with higher numerical stability and accuracy.

￼
