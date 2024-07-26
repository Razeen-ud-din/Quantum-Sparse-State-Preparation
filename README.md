# Quantum-Sparse-State-Preparation
This reporsitory is the submission of the QRE-2024-Challange.

## Introduction 
Welcome to the implementation of Quantum Sparse state preparation algorithm!
This project is the implementation of the research paper [An Efficient Algorithm for Sparse Quantum State Preparation](https://htor.inf.ethz.ch/publications/img/quantum_dac.pdf) by Niels Gleinig and Torsten Hoefle.

## Installation

In order to work with the jupyter notebook of this project `Quantum_sparse_state_prepation.ipynb`, you need a number of packages. The first section of the notebook is about the installation of different packages and modules therein. Running the cells of this section ensure that you are all setup with the environment. The only prerequisite is that you have `python` installed and any IDE that runs `.ipynb` notebook file i.e Visual studio code or jupyter notebook.

## Implementation

The file accompained within this reprsitory named as `Project.pdf` contains all the detailed discussion about the main result of the paper "An Efficient Algorithm for Sparse Quantum State Preparation", the implementation procedure of this paper and the results of implemetation in different langauges i.e`Qsharp` and `qiskit`. Below we provide a brief explanation for the algorithm.

### Input
The input of the algorithm is the classical description of a quantum state i.e we are providing non zero basis states with their respective coefficients.

```[[Basis-1], Probability], [[Basis-2], Probability] , [[Basis-3], Probability]]```

### Output

The outcome of the algorithm is the circuit C having the property when applies to a all zero state provide us the required quantum state.

## Results

### Simulation
The results of the implementation of the above discussed paper in QSharp and Qiskit along with the buitin method for state preparation in these languages is shown in graph below. One an easily see that the result of the implementation are promisisng relative t current method of preparing states in QSharp and Qiskit. 
> Note that our new implmentation has independent of the language and require the same number of gates irrespective of the langauage used.

### Quantum Resource Estimation
