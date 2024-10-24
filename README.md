# Python for Geospatial Analysis

Welcome to Python for Geospatial Analysis! I aim to provide a crashcourse introduction to using Python to wrangle, plot, and model geospatial data. We'll be using libraries such as `geopandas`, `plotly`, `keplergl`, and `pykrige` to these ends.

```{image} docs/logo.png
:width: 250px
:align: center
```

```{note}
The content of this site is adapted from material I used to teach the 2020/2021 offering of the course "DSCI 574 Spatial and Temporal Models" for the University of British Columbia's Master of Data Science Program.
```

## Getting Started

The material on this site is written in Jupyter notebooks and rendered using [Jupyter Book](https://jupyterbook.org/intro.html). However, if you wish to run these notebooks on your local machine, you can do the following:

1. Clone the GitHub repository:
   ```sh
   git clone https://github.com/jswebguru/geospatial-analysis.git
   ```
2. Install the conda environment by typing the following in your terminal:
   ```sh
   conda env create -f py4gs.yaml
   ```
3. Open the course in JupyterLab by typing the following in your terminal:
   ```sh
   cd python-for-geospatial-analysis
   jupyterlab
   ```

```{note}
If you're not comfortable with `git`, `GitHub` or `conda`, feel free to just read through the material on this website - you're not missing out on anything!
``` 
