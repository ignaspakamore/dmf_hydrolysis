# Computation-Guided Exploration of The Reaction Parameter Space of N,N-Dimethylformamide Hydrolysis

This repoasitory contain data files and notebooks used to analyse data and produce ML models for publication: **"Computation-Guided Exploration of The Reaction Parameter Space of N,N-Dimethylformamide Hydrolysis" (10.26434/chemrxiv-2024-tn743)**. 

## Requirements
All libraries used in this work are stored in requirements.txt file. Python version used -  **3.9.0**. 

**Recomended instalation via conda env:**

1. 
```
conda create -n dmf_hydrolysis python=3.9
```
2. 
```
conda activate dmf_hydrolysis
```
3. 
```
pip install -r requirements.txt
```

## data/ directory

* Contains data from distinkt ChemSPX runs (Batches).
* Data used for ML training.
* Corected data using converter notebooks. 

## ML/ directory

Contains notebook used to generate predictive LightGBM model.

## Converter/ directory 

Contains notebooks used to update data set and add pKa values. 

