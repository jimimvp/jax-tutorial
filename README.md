# The JAX Tutorial

Follow these installation steps.

## 0. Python

We'll use Python `3.7.10` One option to install it is using [https://github.com/pyenv/pyenv-installer](pyenv) or install it locally however you see fit.

## 1. Dependencies


Option 1 (virtual envs are highly recommended though):
```shell
pip3.7 install -r requirements.txt
```

Option 2:
for the fancy people is using [https://python-poetry.org/](poetry).
Once you install poetry, you can run this in the project root:
```bash
poetry install 
poetry shell
```


## 2. Jupyter

If everything went well with the installation, you should be able to run this in the terminal, then open up the notebook in the browser (run in root folder of project):
```bash
python3.7 -m ipykernel install --user --name jax-tutorial
jupyter notebook
```

Next steps, open up `tutorial.ipynb` in jupyter notebook, select `jax-tutorial` and follow along.

