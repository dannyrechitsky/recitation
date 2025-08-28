# Brandeis CS231 Recitation

This repository contains exercise materials (mainly as Jupyter Notebooks) to help
students understand course knowledge.

## Style

The repository contains most of Jupyter notebooks for interactive execution and
few of python scripts when necessary. The directory `recitation_core` is a python
package that contains core modules to be imported in the notebooks.

The repository uses a simply flat directory structure, i.e. all scripts and
notebooks are in the directory root, so importing local python modules would be easy.

All notebooks are following the convention: `recitation_<num>_<intro>.ipynb`, so
you'll easily find one you need to exercise on.

## Usage

### Running a Jupyter Notebook

The Jupyter kernel has already prepared for you (checkout `dependency-group` in `pyproject.toml`), so simply run the command:

```
uv run --with jupyter jupyter lab
```

The notebook would be launched at `http://localhost:8888/lab`

### Running a python script

Simply execute command

```
uv run <script_name>.py
```
