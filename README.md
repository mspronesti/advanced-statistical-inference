# Advanced Statistical Inference 

This course focuses on the principles of learning from data and quantification of uncertainty, by complementing and enriching the Introduction to Statistical Learning course. 
The presentation of the material follows a common thread based on the probabilistic data modeling approach, so that many classical algorithms, such as least squares and k-means, can be seen as special cases of inference problems for more general probabilistic models. Taking a probabilistic view also allows the course to derive inference algorithms for a class of nonparametric models that have close connections with neural networks and support vector machines. 

This advanced course is complemented by these lab sessions to guide students through the design and validation of the methods developed during the lectures.

### Google Colab

You can edit and execute these notebooks using [Google Colab](https://colab.research.google.com/). Just click on the icon to open the corresponding notebook in Colab. 

|||
|:--|:--|
| Bayesian linear regression    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mspronesti/advanced-statistical-inference/blob/master/bayesian_linear_regression/Bayesian_Linear_Regression.ipynb)|
| Gaussian process regression   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mspronesti/advanced-statistical-inference/blob/master/gaussian_process/Gaussian_Process_Regression.ipynb)|
| Logistic regression with MCMC | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mspronesti/advanced-statistical-inference/blob/master/mcmc_logistic_regression/Bayesian_Logistic_Regression_MCMC.ipynb)|
| Variational inference         | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mspronesti/advanced-statistical-inference/blob/master/variational_inference/Variational_Logistic_Regression.ipynb)|
| Probabilistic PCA         | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mspronesti/advanced-statistical-inference/blob/master/probabilistic_pca/Probabilistic_PCA.ipynb)|
| Final Assignment | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mspronesti/advanced-statistical-inference/blob/master/final_assessment/Santander_Customer_Transaction.ipynb)|


### Local Jupyter

You can clone the development environment using Conda (installation guide [here](https://docs.conda.io/en/latest/miniconda.html)), by running

```shell
> conda env create --file=environment.yml
```

Once the installation has completed, you can activate the new environment with 

```shell
> conda activate asi
```

Finally launch Jupyter Lab with 
```shell
> jupyter lab 
```
