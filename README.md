# 3-Qubit Quantum Energy Teleportation Protocol

This repository contains the source code, mathematical proofs, and the associated research paper for the **3-Qubit Quantum Energy Teleportation (QET) Protocol**. This work introduces a novel approach utilizing a 3-qubit system to significantly enhance energy retrieval efficiency using superconducting qubits.

## 📄 Abstract

Quantum Energy Teleportation (QET) leverages quantum entanglement to transfer energy between distant locations without physical movement. While previous 2-qubit realizations achieved ~35.4% efficiency, this work presents a completely new 3-qubit approach using a ground state Ising Model Hamiltonian.

Our results demonstrate distinct advantages in energy retrieval:
* **MISO (Multiple-Input Single-Output):** ~32.5% efficiency.
* **SIMO (Single-Input Multiple-Output):** ~67.5% efficiency, a significant improvement over previous models.

The protocol was validated using IBM Quantum hardware (`ibm_brisbane`, `ibm_kyv`, and `ibm_sherbrooke`).

## 📂 Repository Structure

* **`QET_2 (2) (1).pdf`**: The full research paper titled *"3-Qubit Quantum Energy Teleportation Protocol for Significantly High Energy Efficiency Utilizing Superconducting Qubits"*.
* **`3qubitQET.ipynb`**: The main Jupyter Notebook containing:
    * Hamiltonian definition and ground state construction.
    * Qiskit implementation of the QET protocol.
    * Simulation of MISO and SIMO models.
    * Energy calculation and verification.
* **`ground_state_proof (2).ipynb`**: A symbolic mathematical proof (using SymPy) verifying the ground state properties and constraints of the novel Hamiltonian used in the protocol.

## 🛠️ Dependencies

To run the notebooks, you will need the following Python libraries:

* **Qiskit** (for quantum circuit simulation and execution)
* **SymPy** (for symbolic mathematics and Hamiltonian proofs)
* **NumPy** (for numerical calculations)

You can install them via pip:

```bash
pip install qiskit sympy numpy
```

🚀 Usage
Clone the repository:

```Bash
git clone [https://github.com/your-username/3-qubit-qet.git](https://github.com/your-username/3-qubit-qet.git)
```

Open the notebooks: Navigate to the directory and launch Jupyter Lab or Notebook:


Open 3qubitQET.ipynb to see the QET protocol in action and view the energy extraction results.

Open ground_state_proof (2).ipynb to review the mathematical derivation of the ground state.

👥 Authors
Md Shoyib Hassan
M.R.C Mahdy (Corresponding Author: mahdy.chowdhury@northsouth.edu)

Department of Electrical & Computer Engineering, North South University, Dhaka, Bangladesh.

📜 Citation
If you use this code or protocol in your research, please cite our paper:

Md Shoyib Hassan and M.R.C Mahdy, "3-Qubit Quantum Energy Teleportation Protocol for Significantly High Energy Efficiency Utilizing Superconducting Qubits," North South University, 2024.


