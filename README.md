# Chest_disease
Chest disease classification for CT scan


## Command to run the code
run main.py to execute the training


## Venv setup 

conda create -n chest python=3.8 -y
conda activate chest

## Connect DagsHub to Mlflow_dagshub repo

export MLFLOW_TRACKING_URI=https://dagshub.com/rahulsm27/Chest_disease.mlflow 
export MLFLOW_TRACKING_USERNAME=rahulsm27 
export MLFLOW_TRACKING_PASSWORD=45e26a78795667e5d839dcfbb7068925ffadde17 

## DVC cmd
dvc init
dvc repro
dvc dag
