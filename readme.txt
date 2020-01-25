1. About code and demo running
We developed a code measuring differences between (i) a distribution obtained from in-vitro experiments and (ii) a distribution simulated within the code. The experimental data is imported (dataset: 'GradualColonies.xlsx'). The simulated data can be of various sizes. A large size (n_sim=100000) is utilized in the simulations of our research ('code_main_012420.ipynb', 'code_death_012420.ipynb' and 'code_death_randommutation_012420.ipynb'), and a small size (n_sim=100) is in the demo exercise ('code_demo_012420.ipynb'). The time taken to run with n_sim=100 is about 8 minutes, and with n_sim=100000 is about 43 hours. The outcomes are 2 heatmaps showing differences over a range of model parameters, under two different drug administration, crizotinib ('criz_heatmap.png') and lorlatinib ('lorl_heatmap.png') .

2. Required systems/programs 
Python 3 (https://docs.python.org/3.6/whatsnew/changelog.html#python-3-6-3-final), Jupyter notebook, and an operating system (Windows, Mac or Linux) 

Versions used in the research:  
Max OS X 10.11.6
Python 3.6.3 
Jupyterlab 0.27.0

Required python packages: 
numpy, math, scipy.stats, copy, matplotlib, pickle, pandas, seaborn, time

3. Installation
Python: https://www.python.org/downloads/
Jupyterlab: https://jupyter.org/install