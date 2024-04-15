# Quantum-Error-Mitigation-On-a-Variational-Algorithm

This git explores the implementation and effectiveness of quantum error mitigation strategies in variational quantum algorithms, specifically targeting the challenges presented by noise in quantum computations during the Noisy Intermediate-Scale Quantum (NISQ) era. We employ the Variational Quantum Eigensolver (VQE) to address the one-dimensional Fermi-Hubbard model, a significant quantum mechanical problem, under noisy conditions typical of current quantum technologies, in order to find it ground state.

Our approach utilizes error mitigation technique, Zero-Noise Extrapolation, to enhance the fidelity of quantum simulations. Thise method are particularly designed to correct errors induced quantum computers quantum.

Through detailed simulation and theoretical modeling, we demonstrate that our error mitigation strategies significantly improve the accuracy of ground state energy calculations. The report presents a comprehensive analysis of the noise models, the implementation of mitigation technique, and it impact on the quantum computational accuracy.


# Requirement for runing the script.

In order to run this script, you need the data provided in the data file and some Python packages. To do so, you need to run:  
```python
!pip install optax  
!pip install qiskit==0.45.2  
!pip install pennylane-qiskit  
!pip install qiskit-aer  
!pip install qiskit-ibm-runtime  
!pip install penylane  


