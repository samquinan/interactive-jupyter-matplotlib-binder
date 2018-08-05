# Example Binder with Interactive Jupyter Plots using Matplotlib

[![Binder](https://beta.mybinder.org/badge.svg)](https://mybinder.org/v2/gh/samquinan/jupyter-extension/master?filepath=slider.ipynb)

This is a example binder that includes interactive Jupyter-matplotlib plots and uses a conda-based env setup. The code is based on the [matplotlib widgets slider demo](https://matplotlib.org/examples/widgets/slider_demo.html) but has been modified to use the Jupyter ipywidgets for interaction.

As a binder, this current example only works in the Notebook renderer, not JupyterLab. This requires installing the conda-forge packages for:

- matplotlib
- ipywidgets
- widgetsnbextension
- ipympl (i.e., [jupyter-matplotlib](https://github.com/matplotlib/jupyter-matplotlib))

While nothing the notebook itself prevents the use of JupyterLab, I simply haven't gotten the environment setup for that working properly.