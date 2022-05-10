# antarctic\_subantarctic\_asteroidea\_isotopes


This repository contains short code to transform raw data of dataset `Stable isotope ratios of C, N and S in Southern Ocean sea stars (1985-2017)`


## Dataset decription

The raw data is available at Zenodo:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5041318.svg)](https://doi.org/10.5281/zenodo.5041318)

Darwin Core formatted of this dataset is published in the portals below. 

portal | link
:-- | :--
IPT | https://ipt.biodiversity.aq/resource?r=antarctic_subantarctic_asteroidea_isotopes
GBIF | https://www.gbif.org/dataset/ff3984d7-84bd-4f3a-b843-666faa4c1696
OBIS | https://obis.org/dataset/c6b9cd54-3c38-4054-b5e6-d331414d5899

## Repo structure

```
.
├── README.md 			: description of this repository
├── SO_isotopes.Rproj	        : R Project
├── data			: directory to store data
│   └── processed		: directory to store processed data
├── html			: HTML of knitted Rmd files
│   └── transform-data.html	
├── renv 			: renv files for dependencies
├── renv.lock			: describe the state of project's library
└── src
│   └── transform-data.Rmd	       : Rmarkdown file of the code
```

Knitted Rmarkdown can be rendered at https://raw.githack.com/biodiversity-aq/antarctic_subantarctic_asteroidea_isotopes/main/html/transform-data.html

## Getting started

If dependencies are not automatically installed by `renv` when you open `SO_isotopes.Rproj`, try the following command.

```{r}
renv::restore()
```
You can run chunks of R code in `transform-data.Rmd` or knit them into html.
