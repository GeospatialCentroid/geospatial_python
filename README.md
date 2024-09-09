The following jupyter notebooks have been adapted from the carpentries material [Introduction to Geospatial Raster and Vector Data with Python](https://carpentries-incubator.github.io/geospatial-python/)

Episodes 5-8 have been covered:
* 5 Access satellite imagery using Python
* 6 Read and visualize raster data
* 7 Vector data in Python
* 8 Crop raster data with rioxarray and geopandas

Each with a working and complete notebook for use in workshop instruction.

For these notebooks to work a 'geospatial' environment must we created which includes all the necessary libraries.


## Installation
1. Start by downloading and installing [python](https://www.python.org/downloads/)
1. Then create a virtual environment and install all the dependances.
Setting-up the virtual environment can be done from the terminal on osx and linux with the following commands:
```
python3 -m venv geospatial
source venv/bin/activate
python3 -m pip install -r requirements.txt

```
Then execute

```jupyter lab```

To launch JupyterLab

---
Alternatively, with [Anaconda](https://www.anaconda.com/) installed the following steps can be used:

1. From the Anaconda Navigator click the "Environments" button on the left.
1. Then from the bottom of the screen, click Import.
1. From the popup that appears, click the folder icon next to the local drive text field and choose the "geospatial_environment.yaml" downloaded as part of this repo.
1. Accept the default name, then click the "Import" button from the popup and wait while the environment is created.
1. Make sure the "geospatial" environment is selected and then launch jupyter lab

Conda can also be used for the [software setup](https://carpentries-incubator.github.io/geospatial-python/#software-setup).