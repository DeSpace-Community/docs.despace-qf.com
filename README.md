# docs.despace-qf.com

Documentation for the DeSpace quadratic funding community

## Locally install and view the docs

Requirements
 - poetry (python package and virtual env manager)

Steps to compile and browser the docs:
 - (First time only): `poetry install`
 - `poetry shell`
 - (make sure you are in the right folder)
 - `make html`
 - `cd build/html`
 - `python -m http.server --bind 127.0.0.1`


