F2019_IS590DV_FinalProject [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tretomaszewski/F19_IS590DV_Final/master?filepath=notebooks%2FIS590DV_Fa19_Final_Presentation.ipynb)
==============================

Fall 2019 IS590DV Data Visualization Final Project

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the environment, e.g.


Setup
-----

If you have `conda` you can use `environment.yml` [to clone the environment used with this project.](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)

1. In the project root directory on command line, clone the environment:

        conda env create -f environment.yml
        conda activate dataviz
        pip install -r requirements.txt

2. Now to [setup the environment](https://stackoverflow.com/questions/53004311/how-to-add-conda-environment-to-jupyter-lab) for JupyterLab, run these commands.
    `ipykernel`, and`ipympl` may or may not be necessary depending on your setup. `dataviz` is a good name for the kernel.

        conda install ipykernel
        ipython kernel install --user --name=<any_name_for_kernel>

3. Then, still in the project root, start up JupyterLab.

        jupyter lab

4. Once in JupyterLab, navigate to the `notebooks` directory and select `SmartPhoneWatchActivity.ipynb`.

5. If prompted for a kernel environment, choose the one used for `<any_name_for_kernel>`.
    If **not** prompted and the notebook won't run, try changing the kernel environment in the upper right-hand corner.

6. Finally, if things still do not work, deactivate the dataviz environment

        conda deactivate
        conda install -c conda-forge nb_conda_kernels

    And return to **Step 2**.

