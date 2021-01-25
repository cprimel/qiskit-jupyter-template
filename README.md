<p style="text-align: center;">
<img src="https://github.com/Qiskit/qiskit.org/blob/3633ec63a67ca44b2ec293682ec06535e253a633/static/images/qiskit-logo.png" height="100px" alt="logo"/> + <img src="https://github.com/jupyter/jupyter.github.io/blob/master/assets/main-logo.svg" height="100px" alt="logo"/>
 </p>
<h1 style="text-align: center;">qiskit-jupyter-template</h1>
<div style="text-align: center;">
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