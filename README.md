# gdi-data-visualization-python
Repository for talk on data cleaning, manipulation and visualization in Python for the GDI Cohort Program

## Getting started
This repository requires `python` to be installed, `python3.5+` is recommended. `pip` is also required.

To get started, clone this repository onto your local machine and navigate to it. Using a python virtual environment is recommended. Run the following command to install the required python packages.

```{bash}
python -m pip install -r requirements.txt
```

If you are using jupyter notebook, then you can set up your kernel as follows:

```{bash}
python -m ipykernel install --user --name=gdi-viz-seminar
```

Followed by running the following to launch the Jupyter server:

```{bash}
jupyter notebook
```

Click the link in your terminal and the notebook should open in your browser.

The data is located in the `data/` directory, the original raw data set located in `data/raw/` and the cleaned data set in `data/processed/`.

There are three jupyter notebooks in the `notebooks` folder, split into their functions. One for data cleaning, one for visualization and finally one for modeling/prediction.
