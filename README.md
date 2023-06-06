# Neural_Network_Charity_Analysis
Module 20 Challenge, Neural Networks and Deep Learning Models - UNCCH Data Analytics Bootcamp, Spring 2023


## Project Overview

### Purpose
In this exercise, I assisted Beks to create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Method
Python libraries from "pandas", "scikit-learn", and "tensorflow" were used to perform the analysis. 
The data needed to be read in from a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. A density plot was then employed to determine how frequent unique values in the APPLICATION_TYPE and CLASSIFICATION columns appeared, which were then used to determine the threshold for replacing insignificant counts with "other". 

From the Module 20 Challenge:
```
    Part 1: Preprocessing Data for a Neural Network Model
    Part 2: Compile, Train, and Evaluate the Model
    Part 3: Optimize the Model
    Part 4: Save and export model as a HDF5 file
```

### Jupyter Notebook
- Link to notebook files for analysis in Jupyter Notebooks:
    - [AlphabetSoupCharity](AlphabetSoupCharity.ipynb)

## Results

### Density Plot for "Application Type"  

- ![application_count](/application_count.png)

### Optimization
I attempted to optimize the model to acheived a target predictive accuracy higher than 75% using several methods including using "tanh" as one of the hidden layers, adjusting the number of neurons on the "relu" and "sigmoid" hidden layers, increasing the bin size, and adding more epochs. Several of these made aslight difference, but ultimately I could not get the model to produce an accuracy above 72.5%. 

- ![final_accuracy](/final_accuracy.png)

### Output File
- [AlphabetSoupCharity](AlphabetSoupCharity.h5)

