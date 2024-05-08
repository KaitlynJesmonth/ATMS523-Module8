# ATMS 523 Module 8
This repository hosts code for the ATMS 523 - Weather and Climate Data Analytics final project. A random forest regression was used to help predict snow-to-liquid ratios at the Albany International Airport in New York. The dataset used in this analysis is from [NCEI Global Historical Climatology Network - Hourly (GHCNh)](https://www.ncei.noaa.gov/products/global-historical-climatology-network-hourly). Lastly, different XAI techniques like feature importance, permutation analysis, and SHAP analysis were included in this module.

## Setting Up
In order to complete this module in Python, [scikit-learn](https://scikit-learn.org/stable/) will be used. 

The package can be installed using [conda](https://docs.conda.io/projects/conda/en/latest/)
```
conda install -c conda-forge scikit-learn
```

Also, [SHAP](https://shap.readthedocs.io/en/latest/index.html) will be used in the analysis shown in this module.

This package can be installed using [conda](https://docs.conda.io/projects/conda/en/latest/)
```
conda install -c conda-forge shap
```

## Demo the code
Run the `Module8.ipynb` file to demo the code. A copy of the random forest model that produced the results in this notebook can be loaded in using the `random_forest.joblib` file.

## Data
The `GHCNh_USW00014735_por.psv` dataset will need to be downloaded by running the second code cell in the jupyter notebook.

## Key functionalities
- Random forest regression model
- Mean Decrease in Impurity (MDI) feature importance
- Multipass Permutation Analysis
- SHAP Analysis
- Calculation of correlation coefficient and root mean square error statistics

## Maintenance of the Project
This code was written for my graduate-level class at the University of Illinois and is completed at this time.

## References and Acknowledgements
NCEI, 2024: Global Historical Climatology Network - Hourly. Accessed 01 May 2024, https://www.ncei.noaa.gov/products/global-historical-climatology-network-hourly.  

Scikit-learn: Machine Learning in Python, Pedregosa et al., JMLR 12, pp. 2825-2830, 2011.

SHAP: Lundberg, S. M., and S.-I. Lee, 2017: A Unified Approach to Interpreting Model Prediction. Adv. Neural Information Process. Syst., 4765–4774, http://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions.pdf.