# Qiskit Project Template 
A template for submitting your Qiskit projects to CMC.


## Getting Started

### 1. Setup Python environment

Begin by creating a new Python environment. You set up a Python virtual environment `venv` or a Conda environment and use `pip` or `conda`.

```bash
# Create a new conda environment
conda create -n qiskit_env python=3.x

# Activate the conda environment
conda activate qiskit_env
```

### 2. Clone this repository

Once the Python environment is activated, the template can be cloned using `git`.

```bash
git clone https://github.com/CMC-Quantum/Qiskit-Project-Template.git
```

### 3. Install and update dependencies

Install the `Qiskit>1.0.0` packages from the `requirements.txt` file. 

```bash
pip install -r requirements.txt
```

Note: If your project requires additional packages, install them as needed and update the `requirements.txt` file with their latest versions.

```bash
# Update requirements.txt
pip install pipreqs
pipreqs . --force
```

### 4. Start your project

1. Place all your source code in the `project/` or `src/` directory.
2. Store input datasets in the `data/` directory. Ensure the files are named descriptively and consistently for clarity.
3. Save results from simulator or hardware execution in the `results/` directory.

Optionally, you can build a Jupyter notebook workflow to demonstrate your project. This will provide CMC with a clear and interactive view of your workflow. Save the Jupyter notebooks in the `notebooks/` directory. 

## Support

For questions or issues, please contact the repository maintainers or open an issue on GitHub.