# Forest Classification With Random Forest and Neural Network
By Phil Gagnon, Kai Ding\
Date: Apr 15, 2023
----

### Table Of Contents:
- [Description](#description)<br>
    - [About the project](#about-the-project)<br>
    - [Repo files](#repo-files)<br>
    - [Highlights and learnings](#highlights-and-learnings)<br>
- [Running Project](#running-project)<br>
    - [Requirements](#requirements)<br>
    - [Execution](#execution)<br>

----

### Description

#### About the project
This project is based on a **<a href="https://www.kaggle.com/c/forest-cover-type-prediction" target="_blank">Kaggle competition</a>**, to predict 7 forest cover types from cartograpgic variables, including numeric, binary, and categorical variables. The data set includes 15,120 observations and 54 features/columns. 

#### Repo Files
- `Phil_Kai_EDAv5_added_comments.ipynb`: This is the final jupyter notebook
- `forestcover.csv`: The forest cover-type dataset. 
- `Final Presentation.pdf` : PDF version of final presentation for highlights and key findings.

#### Highlights
- Feature Engineering: Created 8 new features, 5 of which ranked in Top 10 important features by MI score
- Model Performance: Neural Network achieved Training/Test accuracy of 78%/77% respectively; Random Forest
acheived Training/Test accuracy of 86%/81%.
- Classification by Cover Type: Type 4 and 7 are easier to predict, while most misclassifications happened between Type 1/2/5 and Type 3/6.

----

### Running Project

#### Requirements

This project requires **Python 3.11** and the following Python libraries installed:

- [Python 3.11.3](https://www.python.org/downloads)                          (Coding Language)
- [NumPy](http://www.numpy.org/)                                            (For Scientific Computing)
- [Pandas](http://pandas.pydata.org)                                        (For Data Analysis)
- [matplotlib](http://matplotlib.org/)                                      (For Visualization)   
- [seaborn](https://seaborn.pydata.org/installing.html)                     (For Visualization)
- [scikit-learn](http://scikit-learn.org/stable/)                           (ML Library for Python)
- [tensorflow](http://tensorflow.org/install/)                              (Deep Learning Library)

#### Execution

In a terminal or command window, navigate to the top-level project directory `Forest_Cover-Type` (that contains this README) and run one of the following commands:

```bash
ipython notebook Phil_Kai_EDAv5_added_comments.ipynb
```  
or
```bash
jupyter notebook Phil_Kai_EDAv5_added_comments.ipynb
```
or if you have 'Jupyter Lab' installed
```bash
jupyter lab
```

-----
