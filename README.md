# PQC migration workshop

Hands-on workshop materials for exploring Post-Quantum Cryptography (PQC), using the Python implementation provided by  
https://github.com/GiacomoPope/dilithium-py.

[![Launch on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/piabauspiess/pqc-workshop/main?filepath=notebooks%2Fdilithium_intro.ipynb)

> No local installation required — click the Binder badge above to run the notebooks directly in your browser.

---

## Repository structure

- `notebooks/` — the Jupyter notebooks for the workshop  
- `environment.yml` — conda environment for running the notebooks locally  

---

## Run locally

### Prerequisites

Please ensure you have:

- git  
- conda

---

### 1. Clone the repository

```bash
git clone https://github.com/piabauspiess/pqc-workshop.git
cd pqc-workshop
```

---

### 2. Create the conda environment

```bash
conda env create -f environment.yml
conda activate pqc-workshop
```

---

### 3. Start Jupyter

```bash
jupyter notebook
```

(or use `jupyter lab` if preferred)

This will open a browser window.

---

### 4. Open the notebooks

In the browser:

1. Navigate into the `notebooks/` folder  
2. Open the notebook you want to run  
3. Select **Kernel → Restart & Run All**  

---

## Troubleshooting

If Jupyter is not found, make sure the environment is activated:

```bash
conda activate pqc-workshop
```

If the environment creation fails, verify that your conda installation is up to date:

```bash
conda update -n base -c conda-forge conda
```

---

## License

(Add your preferred license here, e.g., MIT License.)