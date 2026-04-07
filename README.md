# wekeo-earthkit
 
**wekeo-earthkit** is a collection of Python-based code 
designed to provide introductory training on the use 
of the [earthkit WEkEO plugins]('https://earthkit-data.readthedocs.io/en/latest/examples/wekeo.html') for the [earthkit python package](https://github.com/ecmwf/earthkit). This module is designed to stand-alone but also forms parts of wider 
WEkEO training activities.

## License
 
This code is licensed under an MIT license. 
See file LICENSE.txt for details on the usage and distribution terms.

All product names, logos, and brands are property of their respective owners. 
All company, product and service names used in this website are for 
identification purposes only.
 

## Authors
* [**Anna-Lena Erdmann**](mailto://annalena.erdmann@eumetsat.int) - *Initial development* - [EUMETSAT](http://www.eumetsat.int)

 
## Getting Started
  
The course is based on [Jupyter notebooks](https://jupyter.org/), which allow
a high-level of interactive learning, as code, text description and 
visualisation is combined in one place. If you have not worked with 
`Jupyter Notebooks` before, you can look at the module 
[Introduction to Python and Project Jupyter](./welcome_to_wekeo_jupyterlab.ipynb) 
to get a short introduction to the WEkEO Jupyter Lab workspace.

### Prerequisites
 
If you are working on a local machine, you will require Jupyter notebook to run this code. We recommend that you install the
latest Anaconda Python distribution for your operating system (https://www.anaconda.com/). 
Anaconda Python distributions include Jupyter Notebook. We recommend setting up an
environment as recommended below, however you may also adapt your current Python 
environment to include the dependencies listed.

You can create the recommended environment with:

```bash
conda env create -f environment.yml
conda activate wekeo-earthkit
```
 
### Dependencies

| Package   | Version | License      | Link                                                                 |
|-----------|---------|--------------|----------------------------------------------------------------------|
| python    | 3.11.11 | PSF-2.0      | [python.org](https://www.python.org/)  |
| cartopy | 0.24.0 | BSD-3-Clause | [anaconda.org/conda-forge/cartopy](https://anaconda.org/conda-forge/cartopy) |
| earthkit-data | 0.19.3 | Apache-2.0 | [anaconda.org/conda-forge/earthkit-data](https://anaconda.org/conda-forge/earthkit-data) |
| earthkit-plots | 0.6.1 | Apache-2.0 | [pypi.org/project/earthkit-plots](https://pypi.org/project/earthkit-plots/) |
| fsspec | 2024.6.1 | BSD-3-Clause | [anaconda.org/conda-forge/fsspec](https://anaconda.org/conda-forge/fsspec) |
| hda       | 2.34    | Apache-2.0   | [anaconda.org/conda-forge/hda](https://anaconda.org/conda-forge/hda) |
| ipykernel | 6.29.5 | BSD-3-Clause | [anaconda.org/conda-forge/ipykernel](https://anaconda.org/conda-forge/ipykernel) |
| ipython | 8.29.0 | BSD-3-Clause | [anaconda.org/conda-forge/ipython](https://anaconda.org/conda-forge/ipython) |
| matplotlib | 3.9.2 | PSF-2.0 | [anaconda.org/conda-forge/matplotlib](https://anaconda.org/conda-forge/matplotlib) |
| numpy | 1.26.4 | BSD-3-Clause | [anaconda.org/conda-forge/numpy](https://anaconda.org/conda-forge/numpy) |
| pandas | 2.2.3 | BSD-3-Clause | [anaconda.org/conda-forge/pandas](https://anaconda.org/conda-forge/pandas) |
| pip  | 24.3.1  | MIT    | [anaconda.org/conda-forge/pip](https://anaconda.org/conda-forge/pip)  |
| xarray | 2024.5.0 | Apache-2.0 | [anaconda.org/conda-forge/xarray](https://anaconda.org/conda-forge/xarray) |
| zarr | 2.18.3 | MIT | [anaconda.org/conda-forge/zarr](https://anaconda.org/conda-forge/zarr) |

`earthkit-plots` is installed via `pip` from within the conda environment because it is not currently distributed on `conda-forge`.
