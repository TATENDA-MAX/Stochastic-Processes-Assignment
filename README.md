Markov Chain Analysis
Project Overview
This repository contains a Jupyter Notebook (or Google Colab notebook) that explores various concepts related to Markov Chains. The notebook addresses several problems, including:

Problem A1: Analysis of a 5-state Markov chain, identifying recurrent/transient states, periods, steady-state probabilities, and ergodicity.
Problem A2: Analysis of a 7-state Markov chain, focusing on recurrent classes, transient states, periods, limiting probabilities, and ergodicity.
Problem A3: Simulation and analytical calculation for a time-varying traffic Markov chain.
Setup and Installation
To run the notebook, you will need an R environment with the following packages installed:

install.packages(c("markovchain", "expm", "diagram", "ggplot2", "reshape2"))
If running in Google Colab, the necessary installation steps are included at the beginning of the notebook.

Usage
Open the .ipynb file in Jupyter Notebook or Google Colab. Run the cells sequentially to follow the analysis for each problem. Each section includes comments and explanations of the code and results.

Results and Discussion
Problem A1: 5-State Markov Chain
Identified State '1' as an absorbing recurrent state.
Demonstrated rapid convergence to State '1' in the long run.
Problem A2: 7-State Markov Chain
Identified a recurrent class {'1', '2'} and several transient states.
Showed that the chain is not ergodic due to reducibility and periodicity.
Problem A3: Traffic Markov Chain
Calculated the distribution of traffic states at 6 PM analytically and verified it through simulation.
The analysis highlights the impact of changing transition probabilities over different time periods.
