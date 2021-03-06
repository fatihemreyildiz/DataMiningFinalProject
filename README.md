# Team Samaritan - CENG 3521 Data Mining - Final Project
 
## Team & Roles
### Halil İbrahim Ceylan 390709073 [[haliliceylan](https://www.github.com/haliliceylan)]
- Linear Classification (Logistic Regression, Perceptron, etc.)
- Neural Network-based Classification
- Report
### Fatih Emre Yıldız 180702004 [[fatihemreyildiz](https://www.github.com/fatihemreyildiz)]
- Data Preprocessing
- Clustering
- Report

## Structure
- `/` -> It is the Folder that has all the source code and report. 
- `/dataset` -> It is a folder that has raw dataset and dataset for weka (.arff format)to analyze 
- `/graphs` -> There are all the graphs that has been created by source codes and weka graphics.
- `/wekaoutputs` -> It has extra files not included to the reports. There are informations that we needed during the development. 
- `/final.py` -> Python Source Code 
- `/final.ipynb` -> Jupyter Notebook Source Code 
- `/Report.text` -> Latex Report File
- `/Report.pdf` -> Rendered Latex Report File in PDF format
- `/requirement.txt` -> All dependencies for development environment

## Language, version, and main file
- `python >= 3.8.5` 
- final.py 
- We used Virtual Environment for the environment, you can find environments setup codes below.



## Project Development Environment Setup
**Hint:** You can use also final.ipynb with jupyter (included in environment) for comfortable environment

**Setup:**
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirement.txt
```
**Run the Code Directly:**
```bash
python final.py
```

**Run the Jupyer:**
```bash
jupyter-lab
```


## Project's Topic
Electronic Sports - League of Legends

## Project's Goal
Try to guess the winner team

## Project's Description
We are going to use almost every data in the game. We don't know which parameter will be really effective to guess the end of the game. Our most known parameters are The gold which teams earn during the game, towers, inhibitors, wards, monsters killed for both teams, wards replacement, firstblood firstower and so on. We will explain the parameters better on our report. Our dataset is this:
https://www.kaggle.com/gyejr95/league-of-legends-challenger-ranked-games2020
There are almost 200.000 games.
We do not know about which loss function we are going to use. We will decide it later on while we are doing the project.

## Project's Subjects
- [x] Data Preprocessing, 
- [x] Linear Classification (Logistic Regression, Perceptron, etc.), 
- [x] Neural Network-based Classification, 
- [x] Clustering
