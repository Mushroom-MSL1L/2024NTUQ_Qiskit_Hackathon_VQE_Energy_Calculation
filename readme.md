# Qiskit Hackathon Taiwan 2024 --- Efficient Ground State Energy Calculation of LiCoO2 using Variational Quantum Eigensolver
* Group 9
## setup and env
* Only for python 3.11 version.
* Download by ```pip install -r requirements.txt``` first.
* Then you need to install external github library for active space calculation.
    * link : https://github.com/HQSquantumsimulations/ActiveSpaceFinder

## introduction 
* ```Notice``` : We only aim to provide the result and validity of the code.
* We want to using VQE to calculate the ground state energy of LiCoO2 ion battery. 
* However, the size of the molecule is too large to calculate the ground state energy directly. 
* In order to reduce the calculation cost, we using following method to reduce the size of the molecule.
    * Using active space to select the most important orbitals, and only calculate the energy of these orbitals.
    * Using $Z_2$ symmetry to reduce the size of the Hamiltonian matrix, so that we can reduce the quantum circuit depth.

## Thanks 
* Sincerely thanks for our mentor, leo07010, who give us a lot of help and guidance.