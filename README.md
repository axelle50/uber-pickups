# Project with Jedha

Imagine working for Uber: "One of the main pain point that Uber's team found is that sometimes drivers are not around when users need them. [...] Therefore, Uber's data team would like to work on a project where their app would recommend hot-zones in major cities to be in at any given time of day." Paris on April 2022. 

## Objective
The objective is to create algorithms that will determine where are the hot-zones that drivers should be in. Therefore:

- Create an algorithm to find hot zones
- Visualize results on a nice dashboard

## Dataset
The dataset was given by Jedha [New York City pickups](https://full-stack-bigdata-datasets.s3.eu-west-3.amazonaws.com/Machine+Learning+non+Supervis%C3%A9/Projects/uber-trip-data.zip).

## Prerequisites

### Build database

```

### Dependencies
- The source code is written in Python 3.
- The python packages can be installed with pip : `pip3 install -R requirements.txt`

## Usage
### Make_dataset.ipynb 
**Extracts the dataset from the SQL database**
- Input file : features_info.csv
- Output file : dataset_with_labels.csv (not hosted on this repository, you have to create it yourself)

### Explore_dataset.ipynb
**Automates some computations of basic statistics and plots for each feature in the dataset**
- Input file : dataset_with_labels.csv

### Train_models.ipynb
**Trains some multiclass classifiers from different packages (scikit-learn, keras, XGBoost) and compare their performances**
- Input file : dataset_with_labels.csv

## Team contributors
R. Barthélémy
A. Beinrucker
L. Cetinsoy
B. Chousterman
S. Falini
M. Jamme
M. Kovanis
A. Mutschler
M. Naeem

## References
[1] MIMIC-III, a freely accessible critical care database. Johnson AEW, Pollard TJ, Shen L, Lehman L, Feng M, Ghassemi M, Moody B, Szolovits P, Celi LA, and Mark RG. Scientific Data (2016). DOI: 10.1038/sdata.2016.35. 
