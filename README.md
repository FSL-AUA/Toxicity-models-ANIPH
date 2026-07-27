ANIPH Machine Learning Models

This repository contains the machine learning workflow developed in the ANIPH project for predicting Toxicity of PHBV polymers. Models are developed for short-chain-length PHAs (sclPHAs).

Each subfolder corresponds to a specific property/material combination and contains:

Original dataset (*_updated.xlsx)

Preprocessing notebook (*_data_preprocessing.ipynb)

Cleaned dataset (*_data.csv) Dataset obtained after preprocessing (cleaning, filtering, unit harmonization, removing invalid samples).

Training and testing classification model notebook (*_pycaret.ipynb)

Final model deployment on Jaqpot notebook (*_jaqpot.ipynb)

The deployed models on Jaqpot were trained and optimized using Binary Classification models and tailored to the available experimental data.
