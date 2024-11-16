# Computation-Guided Exploration of The Reaction Parameter Space of N,N-Dimethylformamide Hydrolysis

This repository contain data files and notebooks used to analyse data and produce ML models for publication: **"Computation-Guided Exploration of The Reaction Parameter Space of N,N-Dimethylformamide Hydrolysis" (10.26434/chemrxiv-2024-tn743)**. 

## Requirements
All libraries used in this work are stored in requirements.txt file. Python version used -  **3.9.0**. 

**Recomended instalation via conda env:**

```
conda create -n dmf_hydrolysis python=3.9
```
```
conda activate dmf_hydrolysis
```
```
pip install -r requirements.txt
```

## Repository directories

### data/

* Contains data from distinct ChemSPX sampling runs (Batches).
* Data used for ML training.

### ML/ 

Contains notebook used to generate predictive LightGBM model.

### Converter/

Contains notebooks used to update water quantities in DMF experimental data set and add pKa values. 

