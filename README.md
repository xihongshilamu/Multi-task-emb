## Installing the Python package

We only support installation via pip right now.

Installation within virtual environments are recommended, see
[virtualenv](https://virtualenv.pypa.io/en/latest/) or
[conda](https://conda.io/docs/user-guide/tasks/manage-environments.html).

For conda, here's a one-liner to set up an empty environment
for installing Cell BLAST:

`conda create -n cb python=3.9 && conda activate cb`

Then follow the instructions below to install Cell BLAST:

1. Install Cell BLAST from PyPI by running:

   `pip install Cell-BLAST`

   Or, install an editable dev version by running the following command
   under the root directory of this repo:

   `flit install -s`

2. Check if the package can be imported in the Python interpreter:

   ```python
   import Cell_BLAST as cb
   print(cb.__version__)
   ```
