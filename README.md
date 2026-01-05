# Quantum error correction for unresolvable spin ensembles

This repository contains the numerical codes and data used in the paper: [arXiv:2408.11628](https://arxiv.org/abs/2408.11628)
(Authors: Harsh Sharma, Himadri Shekhar Dhar, Hoi-Kwan Lau)

---

## Repository Structure

### 1. `/`  
This folder contains Python source codes and simulation data used in the paper.

#### Contents:
- `00QEC_Sim.ipynb`: Jupyter(Python) Notebook to simulate quantum memory.
  - Comment and Uncomment different cases/parameters in the notebook to generate the corresponding data.  This generates data required for **Fig. 2c** and **Fig. 2d**.
- `QS_Collective.ipynb`: Jupyter(Python) Notebook to simulate quantum sensing.
  - This generates data required for **Fig. 5**.
- `DistinguishingStates.ipynb`: Python code to simulate how the dephased and no jump states can be distinguished just by using collective control.  
- `NewTotalRecovery.ipynb`: Python code to simulate recovery process on the basis of universal collective control.

#### Dependencies:
- **Python Code**: Required for data post-processing
  - Uses **[QuTiP](http://qutip.org/)** (Quantum Toolbox in Python)

> QuTiP Citation:  
> J. R. Johansson, P. D. Nation, and F. Nori, *Comput. Phys. Commun.* **183**, 1760 (2012);  
> *Comput. Phys. Commun.* **184**, 1234 (2013).

---

### 2. `Data/`  
This folder contains **data** related to the quantum memory and sensing simulations.

---

## Notes

- If you use this code or data in your work, please cite the original paper.
- For issues or contributions, feel free to open a GitHub issue or pull request.
