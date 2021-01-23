# EDDS Paper Reproduction

Repository for the Experiment Design in Data Science course at TU Wien. 
Publication: [Reproducibility Study: On Heavy-User Bias in A/B Testing](https://doi.org/10.5281/zenodo.4459284)
## Content

```
./
├─ Simulations-Optimized.ipynb # Optimized simulations and significance testing.     
├─ Simulations-Original.ipynb  # Original simulations of analysed paper [1].
├─ combination_results.csv     # Results for different parameter combinations.
├─ requirements.yml            # Conda Evironment
```
## Run Simulations
### 1. Conda Environment
To run the simulations you can use conda as environment.
#### 1.1 Import Environment
To import the provided environment run `conda env create -f environment.yml` . 
#### 1.2 Activate Environment
Activate imported environment with `conda activate edds` .

Check [conda documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for futher details. 
### 2. Jupyter Notebook
#### 2.1 Start Notebook
Run `jupyter notebook` in edds environment shell
#### 2.2 View in Browser
View interface with link in standard output.
### 3. Start Simulation

## References
[1] Yu Wang, Somit Gupta, Jiannan Lu, Ali Mahmoudzadeh, and Sophia Liu. 2019.On Heavy-User Bias in A/B Testing. InProceedings of the 28th ACM InternationalConference on Information and Knowledge Management(Beijing, China)(CIKM ’19).Association for Computing Machinery, New York, NY, USA, 2425–2428.   [https://doi.org/10.1145/3357384.3358143](https://doi.org/10.1145/3357384.3358143)
