## Machine-Learning-Binary-Classification-Algorithms

### Repository Contents

Project_Notebook.ipynb - Python Jupyter Notebook containing all the data cleaning, processing, experimentation, and visualization of results.

Project_Report.pdf - Formal report explaining the process of the experiment as well as the final results.

An_Empirical_Comparison_of_Supervised_Learning_Algorithms.pdf - Research Paper by Rich Caruana and Alexandru Niculescu-Mizil that stands as the base of this project and is used to compare and verify findings.

Data Folder - Contains all the datasets used in the project.

### Project Introduction

Binary classifiers are widely used in practical scenarios to predict one out of two labels based on a set of features. For example, one of the studied datasets is used to predict whether or not an office room will be occupied based on light, temperature, humidity, and CO2 level. Classifiers explore data in distinct ways to guess the label of one instance. Such implementations can vary drastically from algorithm to algorithm, resulting in varying performance. The question Caruana and Niculescu-Mizil studied was based around how different classifiers would compare with each other. Being able to replicate their results would not only validate their findings but provide further insight into their method and specific classifier behavior around their parameters, which outlines the objective of this study. Decision trees, KNN, and random forests are the classifiers that will be explored. By changing the dataset structure, as well as parameters for each classifier we will explore when these algorithms work best and how they compare to each other. While classifier performance can be measured from different metrics, this experimentation will focus on the algorithm’s testing accuracy.


