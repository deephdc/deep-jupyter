**repository is frozen. These scripts can now be found in deephdc/deep-start**

Helping scripts for Jupyter Lab/Notebook
=================

jupyter_notebook_config.py
-----------------
   Module to set Jupyter access password from the jupyterPASSWORD environment, if available.
   BASED ON: https://github.com/tensorflow/tensorflow/blob/master/tensorflow/tools/docker/jupyter_notebook_config.py

run_jupyter.sh
------------
   Script to start jupyterlab, also checks jupyterCONFIG_URL environment for more advanced configuration (e.g. download of certificates)
