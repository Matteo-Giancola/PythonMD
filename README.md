# PyMD-Notebook

![Python](https://img.shields.io/badge/python-3.12.7-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

**PyMD-Notebook** is a Jupyter notebook for performing classical molecular dynamics (MD) simulations in Python. It allows users to run MD on a given atomic configuration and analyze the final positions and radial distribution functions (RDF).

## Key Features

### Molecular Dynamics Simulation
- Run **classical MD simulations** starting from a user-provided atomic configuration.
- Evolve atomic positions over time according to interatomic forces.
- Supports **user-defined simulation parameters** (time step, temperature, number of steps, etc.).

### Output Analysis
- Extract **final atomic configuration** after the MD simulation.
- Compute **radial distribution functions (RDF)** to analyze structural properties.
- Plot **RDF** and other observables directly in the notebook.

### Python Compatibility
- Developed in **Python 3.12.7**.
- Compatible with **JupyterLab** and **Jupyter Notebook**.
- Uses standard scientific libraries: **NumPy**, **Matplotlib**, **pandas**, etc.


## Usage
1. Open the notebook in an editor.
2. Load an initial atomic configuration.
3. Set simulation parameters (time step, temperature, number of steps, etc.).
4. Run the MD simulation.
5. Inspect the **final atomic configuration** and plot **RDF** or other observables.

## License
This repository is licensed under the **MIT License**.

