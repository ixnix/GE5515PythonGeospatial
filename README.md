# GE5515: Python for Geospatial Analysis

## Course Description

This course introduces Python programming for geospatial data analysis. Students learn to manage, analyze, and visualize spatial and non-spatial data using open-source Python libraries. Topics span the full geospatial analysis pipeline — from vector and raster fundamentals to advanced applications like watershed delineation and climate data analysis.

## Modules

| Module | Topic | Lecture Notebook(s) | Assignment |
|--------|-------|---------------------|------------|
| 0 | Introduction & Environment Setup | `introduction.ipynb`, `syllabus.ipynb` | — |
| 1 | Pandas Review | `pandas_review.ipynb` | Assignment 1 |
| 2 | Spatial Data Models & Shapely | `data_model.ipynb` | Assignment 2 |
| 3 | GeoPandas | `geopandas.ipynb` | Assignment 3 |
| 4 | Coordinate Reference Systems | `crs.ipynb` | Assignment 4 |
| 5 | Geocoding | `geocoding.ipynb` | Assignment 5 |
| 6 | Spatial Joins | `spatial_join.ipynb` | Assignment 6 |
| 7 | Proximity Analysis | `proximity_analysis.ipynb` | Assignment 7 |
| 8 | Vector Overlay | `vector_overlay.ipynb` | Assignment 8 |
| 9 | Data Aggregation & Reclassification | `aggregation_reclassify.ipynb` | Assignment 9 |
| 10 | Raster Data | `Raster_data.ipynb` | Assignment 10 |
| 11 | Raster Analysis | `Raster_analysis.ipynb` | Assignment 11 |
| 12 | Climate Data with xarray | `xarray_climate_data.ipynb` | Assignment 12 |
| 13 | Aggregating Raster & Vector Data | `aggregate_raster_vector.ipynb` | Assignment 13 |
| 14 | Watershed Delineation | `watershed.ipynb` | Assignment 14 |

## Getting Started

1. Install [Anaconda](https://www.anaconda.com/download) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
2. Create the course environment:
   ```bash
   conda env create -f module_0/environment.yml
   conda activate pythongis
   ```
3. Launch JupyterLab:
   ```bash
   jupyter lab
   ```

## Repository Structure

```
GE5515/
├── module_0/          # Introduction & environment setup
│   ├── data/
│   ├── img/
│   └── *.ipynb
├── module_1/          # Pandas review
│   ├── data/
│   ├── img/
│   ├── pandas_review.ipynb
│   └── Assignment_1.ipynb
├── ...
└── module_14/         # Watershed delineation
    ├── data/
    ├── img/
    ├── basin_functions.py
    ├── watershed.ipynb
    └── Assignment_14.ipynb
```

Each module folder contains:
- **Lecture notebook(s)** — instructional material with worked examples
- **Assignment notebook** — practice problems for students (modules 1–14)
- **`data/`** — datasets used in the module
- **`img/`** — images and diagrams (most modules)

## Acknowledgments

This course was developed building upon the following open educational resources:

- [**Introduction to Python for Geographic Data Analysis**](https://pythongis.org/) by Henrikki Tenkanen, Vuokko Heikinheimo & David Whipp (University of Helsinki). Many of the lecture notebooks and exercises in this course are adapted from their excellent open-source curriculum.
- [**Python for Data Analysis**](https://wesmckinney.com/book/) by Wes McKinney (O'Reilly Media). Foundational reference for the pandas and data wrangling portions of the course.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0).

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

You are free to share and adapt this material for any purpose, provided you give appropriate credit.
