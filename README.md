# Tao's Data Science Portfolio

Welcome to my Data Science Portfolio! This repository contains of projects I have done throughout the years of acadmeic training, self-learning, and voluntary work, etc.

Note: Data used in the projects in this repo is for education and demonstration purposes only.

## About myself

My Data science journey commenced when I first learned about Python. When I was interning for a manufacture company, once I was told to collect as much customer information as possible from a website. My manager told me to do it when I am free since over there are 3000 business names and addresses. 'Copy and paste' is never my way to do things. I did my research and learned about a way to do it in Python. I reached out to my friend, who was majored in CS at college. In just two days, I collected and cleaned up all this business information, handled it over to the CEO of the company and got the first bonus in my professional career. Ever since that, I started helping colleagues around me to 'automate' their repetitive work. I enjoy learning through these Ad-hoc tasks. And later, when I was working as a government consultant for the New York State Government, I realized my interest was and has always been analytics. 

Currently, I am pursuing my Master's degree at the University of Chicago. My coursework and research at the University of Chicago involved multivariate analysis, machine learning algorithms, and matrix computation. My proficiencies in statistical and analytic modeling tools are but are not limited to Matlab, Python, R, and SQL. If you are also a continuous learner and data enthusiast, please connect with me on GitHub, medium or any other platforms. I am looking forward to hearing your stories!

**Medium**: https://medium.com/@tf642228

**Linkedin**: https://www.linkedin.com/feed/

**Github**: https://github.com/TaoFeng1234/Tao_Portfolio



## Table of Contents 

* Machine Learning Impletmentations [Python]
  * [Text Analysis with logisitics Regression from scratch](https://medium.com/@tf642228/text-analysis-with-logistics-linear-model-in-python-35ceeb57f74c)
  
* Supervised Learning Algorithm [Python]
  * [Comparison of different Classifier Models with `sklearn`](https://github.com/TaoFeng1234/Tao_Portfolio/blob/master/CompraisonofClassifers.ipynb)
  
   In this practice, I first compare the performance of different classifier models on a given binary classification task. Then I test how the performance of each of the classifiers varies as the size of the training set increase. 
  
   <img src="image/comparison.png" width = "600">
  
   <img src="image/comparison2.png" width = "600">
  
  Observation: The accuracy for each decision tree, random forest, and AdaBoost starts at a relatively low rate. The accuracy increases as the size of the training dataset increase. The accuracy for logistic regression, LDA, NB, Neural Network, SVM and Gaussion Processes strats high and did not chance much as the size of the training set increases. 
  
  *Reference: https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html#sphx-glr-auto-examples-classification-plot-classifier-comparison-py*
  

  * [Lasso Regression MSE vs Lambda](https://github.com/TaoFeng1234/Tao_Portfolio/blob/master/LassoEstimate.ipynb)
  
  The Lasso object is to minimize RSS($$\beta$$) + $$\lambda\sum_{i}\beta_{i}$$. 
  In this project, I first fit the LR on the training data and calculate the MSE on the training set with $\lambda$ chose from 0 to 0.04 with a step of 0.001. Plot on the left shows different lambda with the corrsesponding training MSE.
  
     <img src="image/lass1.png" width = "450">   <img src="image/lass2.png" width = "450">
   
  With 10-fold cross validation implementomg on the training set to select $\lambda$. Plot on the right above compares the
MSE on the hold-out set with the true MSE which is computed on the test set. The best $\lambda$ value could be achieved around 13.

  * [Decision Tree and Pruning](https://github.com/TaoFeng1234/Tao_Portfolio/blob/master/DecisionTreePruning.ipynb)
  
* Unsupervised Learning Algorithm
  
  * [K - Means[R]](https://rpubs.com/tf642228/665000)

* Statistics [R]
  
  * [Analysis with Missing Data](https://rpubs.com/tf642228/648385)
  * [OLS Analysis with Galapagos-island data](https://rpubs.com/tf642228/657767)

* Nonlinear Optimization (Coming Soon) [MATLAB]

* Variational Methods in Image Processing (Coming Soon) [Python]

* [SQL](https://github.com/TaoFeng1234/Tao_Portfolio/blob/master/SQL_Practice.pdf)

* Ad-hoc Projects 

  * Plot new COVID-19 cases on a bubble map [[R]](https://github.com/TaoFeng1234/Tao_Portfolio/blob/master/MiniProjects/co-vid19%20cases.Rmd)
    
    <img src="image/mar30covidcases.png" width = "600" length = "200">
