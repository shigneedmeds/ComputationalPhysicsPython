#  Machine Learning for Materials Property Prediction

This repository provides an introductory set of materials and code for applying **machine learning (ML)** to **materials discovery**, with a focus on predicting material properties from structural and compositional features.

---

##  Repository Contents

### `ML_Introduction.pdf`

A slide deck titled **"Machine Learning Models for Materials Discovery"**, presented by Marco Fronzi at the University of Sydney.

**Topics covered:**
- Fundamentals of AI and ML in materials science
- Types of ML models: Neural Networks, Support Vector Machines, Random Forests
- Definitions: features, target properties, regression vs classification
- Featurization strategies: composition, structure, graph, electronic structure
- Feature engineering and space separability
- Model training: loss functions, optimization (GD, SGD, Adam)
- Model evaluation: training/testing split, cross-validation
- Comparative discussion: traditional NNs vs Kolmogorov–Arnold Networks (KANs)

>  Useful for students or researchers new to ML for materials science.

---

### `ML_MPPs.ipynb`

A **Jupyter Notebook** implementing a practical workflow for **Materials Property Prediction (MPPs)** using machine learning.

**Includes:**
- Data loading from compressed `.json.gz` format
- Data exploration and preprocessing
- Featurization and descriptor generation
- Training/test splitting and cross-validation
- Model training using standard ML regressors
- Performance evaluation using MAE, MSE, and \( R^2 \)
- Visualization of results

>  Ideal for hands-on ML practice with real data from materials science.

---

### `DataSet.json.gz`

A compressed dataset used in the Jupyter Notebook.  
Contains:
- Structural and compositional descriptors
- Corresponding material property labels (target values)
- In a format ready to be parsed with `pandas` and used for ML workflows

>  The dataset simulates or contains computed/measured physical properties of materials, such as Seebeck coefficients, band gaps, or formation energies.

