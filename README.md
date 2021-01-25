<p align="center">
<img src="https://github.com/Qiskit/qiskit.org/blob/3633ec63a67ca44b2ec293682ec06535e253a633/static/images/qiskit-logo.png" height="100px" alt="qiskit-logo"/>
<img src="media/baseline_add_black_18dp.png" height="36" align="baseline" alt="add-symbol"/>
<img src="https://github.com/jupyter/jupyter.github.io/blob/master/assets/main-logo.svg" height="100px" alt="jupyter-logo"/>
 </p>
<h1 align="center">qiskit-jupyter-template</h1>
<div align="center">
 <strong>
    A quickstart template for running IBM's Qiskit SDK in Jupyter Notebooks
 </strong>
</div>
<br/>

## Requirements

* Python 3.8 (current version of```qiskit-aer``` will not build with Python > 3.8)
* JupyterLab or Jupyter Notebook
* (optional: needed to run jobs on IBM's quantum computers) IBMid and IBM Quantum Experience account

## Instructions

```commandline
pipenv install
pipenv shell
python -m ipykernel install --user --name=qiskit-jupyter
jupyter lab
```

Once in your notebook, navigate to **Kernel->Change kernel** on the drop-down menu and select ```qiskit-jupyter```
kernel. 