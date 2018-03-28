Run using Binder:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/davidas85/jupyter-slides/master?filepath=sec_group_meeting.ipynb)

In order to run the notebooks locally:
1. Install [miniconda](https://conda.io/miniconda.html)
2. Run the following commands from the root of the repo:

    ```
    conda env create
    source activate jupyter_slides
    jupyter notebook
    ```
    If you want to run JupyterLab (way cooler, next-gen environment), replace the third line above with:

    ```
    jupyter labextension install @jupyterlab/plotly-extension
    jupyter lab
    ```
