# MLFlow_UI
Hands-on Experience for mlflow with wine dataset

# Basic setup

## Setup the environment
- clone this repository
- **with virtualenv (recommended)**
  - install virtualenv: `pip install virtualenv`
  - create a new environment: `virtualenv mlflow`
  - activate the environment: `source ./mlflow/bin/activate`
  - run `pip install -r requirements.txt`

## The notebook
- run `jupyter notebook`

## To start MLFlow Server
- 'mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host localhost --port 5000'
