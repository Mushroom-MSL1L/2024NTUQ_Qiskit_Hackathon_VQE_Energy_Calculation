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
* Sincerely thanks for our mentor, leo07010, who give us a lot of help and guidance.\\## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Mushroom-MSL1L"><img src="https://avatars.githubusercontent.com/u/136601880?v=4?s=100" width="100px;" alt="Lu Junyou"/><br /><sub><b>Lu Junyou</b></sub></a><br /><a href="https://github.com/Mushroom-MSL1L/2024NTUQ_Qiskit_Hackathon_VQE_Energy_Calculation/commits?author=Mushroom-MSL1L" title="Code">💻</a> <a href="https://github.com/Mushroom-MSL1L/2024NTUQ_Qiskit_Hackathon_VQE_Energy_Calculation/issues?q=author%3AMushroom-MSL1L" title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
