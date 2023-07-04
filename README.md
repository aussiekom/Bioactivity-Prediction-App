# Bioactivity Prediction Application

### Reproducing this web app
To run this web app on your own computer, do the following steps:

### Create conda environment
Firstly, create a conda environment called *bioactivity* (or your own name)
```
conda create -n bioactivity python=3.7.9
```
Secondly, login to the *bioactivity* environement
```
conda activate bioactivity
```
### Install prerequisite libraries

Download requirements.txt file from this repository

```
pip install libraries
```
```
pip install -r requirements.txt
```

###  Download the acetylcholinesterase_06_bioactivity_data_3class_pIC50_pubchem_fp.csv file from

```
https://github.com/aussiekom/computational-drug-development/tree/main/data
```

### Run code and save the PKL file in the end

The machine learning model used in this web app will firstly have to be generated by successfully running the included in this repo Jupyter notebook **bioactivity_prediction_app.ipynb**. Upon successfully running all code cells, a pickled model called **acetylcholinesterase_model.pkl** will be generated.

###  Launch the app

```
streamlit run app.py
```
