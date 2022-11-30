# Mochi Performance Analysis

This repository contains scripts, notebooks, and utilities to
process JSON files produced by Mochi services when monitoring
is activated.

## Installing and running

To use the scripts and notebooks in this repository, simply
clone it on your local machine, and install a Python virtual
environment as follows.

```
git clone https://github.com/mochi-hpc/mochi-performance-analysis.git
cd mochi-performance-analysis
python3 -m venv env
source env/bin/activate
python3 -m pip install -r requirements.txt
```

This will install the necessary Python packages.
You may then start JupyterLab by running `jupyter lab`,
and open one of the notebooks. Next time you need to open
the notebook, simply call `source env/bin/activate` to reactivate
your environment, then `jupyter lab`.
