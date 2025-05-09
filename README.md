### The virtual environment

The environment used for this analysis is a virtual environment. The original 'python -m venv venv' code didn't work so I adjusted it to 'python3 -m venv venv'

To activate the venv, I used 'source/venv/bin/activate'. For windows, the command is 'source/Scripts/activate

I created a .gitignore file to exclude unnecessary files like the virtual environment and Python cache from Git. 'touch .gitignore'

Added these to the gitignore file: 
            venv/
            __ pycache __/
            .DS_Store
            *.pyc

Install all the required libraries. For this project I installed Pandas, Numpy, Matplotlib, Seaborn and Scikit-learn.

Freeze the dependencies to a requirements text file. 'pip freeze > requirements.txt'

Add, commit and push the projects to github.


### The Data
- There was provided a train set and a validation/test set of the galaxies


### The Analysis Notebook

The aim of this analysis was:
- To determine the demographic and socio-economic variables that influence the Well-Being Index of each galaxy. These variables are such as: existence expectancy years, income indices, education years (actual and expected), population, mortality, unemployment rate and gender inequality indices among others to form 80 possible factors.
- To make predictions on the well-being of the new galaxy members provided given the same demographic and socio-economic factors provided.

The notebook is comprised of 5 parts:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Model Selection and Training
- Prediction



