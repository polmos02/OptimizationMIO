# Exact Sparse Regression 

The goal of this project is to study the exact sparse regression problem with an l_0 constraint.  
The objective is to identify a subset of at most k predictors that best explains the response variable in a
least squares sense.  

This problem is known as best subset selection and has been extensively studied in statistics and
optimization due to its strong interpretability and predictive performance.   
However, the l_0 constraint makes the problem computationally challenging, as it requires searching over many possible subsets of
variables.  

Recent advances in Mixed-Integer Optimization (MIO) have made it possible to solve such problems
more effectively in practice.   
In this work, we focus on the setting where the number of observations
exceeds the number of features - n > p.


File structure:  

MIP.py - python script with implemented methods (MIO, First Order)  

exp_n_p_snr_real.ipynb - Experiment 3 and 4  

synth_data_experiments.ipynb - Experiment 1  

relative_accuracy_vs_time.ipynb - Experiment 1 and 2  

folder plots - visualizations of results of the experiments   
