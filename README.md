# COMPAS Fairness Analysis – Machine Learning Project
The analysis illustrates theoretical results on fairness (Kleinberg et al., 2016) using the COMPAS dataset.
All results are reproducible and the notebook includes detailed explanations of each step.

## Repository / Download / Packages 

All code and data are available here:
https://github.com/Louismoraine/Machine-Learning-Project

The COMPAS dataset is publicly available:
https://raw.githubusercontent.com/propublica/compas-analysis/master/compas-scores-two-years.csv

All Python dependencies are listed in the notebook and can be installed via pip:
pip install pandas numpy matplotlib scikit-learn

## Comments on the code

All code was implemented from scratch, with the goal of illustrating the results of the paper; the analysis was inspired by the methods and concepts discussed in the original work. In particular, post-processing code was implemented to demonstrate the impossibility theorem and the effect on calibration.

All code was adapted to run fully reproducibly in a Jupyter notebook, with comments and Markdown explanations for clarity.
