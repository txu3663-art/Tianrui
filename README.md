# Week 3 Lab: Data Management for Machine Learning

Practical lab materials for Week 3. You will clean, transform, and explore tabular data using Python and Jupyter. By the end of the lab you will be able to load raw data, fix common quality issues, engineer starter features, and document a reproducible workflow.

## Learning goals

1. Load CSV and Excel datasets with Pandas and check basic metadata  
2. Tidy messy tables and reshape using melt and pivot  
3. Handle missing values, outliers, and inconsistent types  
4. Join multiple tables safely and verify row counts  
5. Create first pass features for downstream models  
6. Capture decisions in a clear, reproducible notebook

## Repository layout

- `data` holds input datasets used in the lab  
- `exercises` contains the notebooks you will work in  
- `requirements.txt` lists Python package dependencies

## Quick start

### 1. Set up an environment

```bash
# clone
git clone https://github.com/MScBusinessAnalytics/Week3Lab.git
cd Week3Lab

# create a clean environment with Python 3.10 or newer
python -m venv .venv
# on macOS or Linux
source .venv/bin/activate
# on Windows PowerShell
.venv\Scripts\Activate.ps1

# install dependencies
pip install --upgrade pip
pip install -r requirements.txt
