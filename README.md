# BigDataAnalytics
Repository for the Big Data Analytics lab (will delete after 6 months)

## About the Dataset

From: [Kaggle](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification)

## Setup

pip install virtualenv

python -m virtualenv

source venv/Scripts/activate

pip install -r requirements.txt

### Adding new packages to requirements.txt

Install any package after activating venv

pip freeze > requirements.txt

### Add venv to jupyter

ipython kernel install --user --name=BigDataProject

### Remove venv

jupyter kernelspec uninstall BigDataProject

### List jupyter venvs

jupyter kernelspec list
