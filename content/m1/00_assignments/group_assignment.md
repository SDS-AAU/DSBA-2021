---
title: "M1 (Mandatory) Assignment"
weight: 4
disableToc: true
---

## DSBA 2021 - M1: (Mandatory) Assignment


## Introduction


With the individual assignments, you already performed most of the steps in a typical machine learning pipeline. You **imported** some data, **cleaned** it, **explored** the variables and their relationships using summary statistics and **visualisations**. You also exercised some standard machine learning **preprocessing** procedures such as feature scaling and dealing with missing values. 

You practised **unsupervised**  machine learning techniques for dimensionality reduction (e.g. PCA) and clustering (e.g. KNN) to discover latent relationships between features and groupings of observations. In the final workshop and online material you finally used **supervised** machine learning for regression and classification problems, where you created models to predict an outcome of interest given some input features. 

Now it is time to bring most these steps together and apply them to a setting that you find interesting. This should apply the following tasks. 

- Identify an interesting problem that can be tackled using data science techniques. 
- Select and obtain relevant data to do so. 
- Clean and manipulate the data to make it useful for data science techniques. 
- Carry out an exploratory data analysis to provide intuition into the content of the data, and interesting relationships to be found in it. You might unsupervised ML techniques to discover latent relationships within the data. 
- Use supervised ML techniques to create models that predict an outcome of interest. 
- Document your workflow in a reconstructable manner. 
- Report your findings in an accessible manner. 


## Task description

### Data & Problem identification


In this exercise, you are asked to choose and obtain a dataset you consider interesting and appropriate for the tasks required. Some of you may already have some ideas about interesting datasets. There are many open datasets available on the internet (e.g. kaggle or individual projects like Stanford Open Policing or download some of the Datacamp project datasets) [here a recent list of open data repositories for inspiration](https://towardsdatascience.com/top-sourcesfor-machine-learning-datasets-bb6d0dc3378b)

If you instead want to collect your data (e.g. scraping Twitter or other platforms) – we will not hold you back. However, consider the timeframe. 


**The data should fulfill the following minimum requirements:**


- It should be big enough to be useful for applying data science techniques (rule of thumb: minimum  > 500 observations, > 10 features). 
- It contains an interesting outcome to be predicted via supervised ML. 
- It is not completely trivial and clean, and at least requires a minimum amount of cleaning, munging, preprocessing (eg. no toy dataset such as Iris, diamonds, or cars).  

### Analysis pipeline

The analysis to be carried out by you has to contain elements of data **manipulation, exploration, unsupervised and supervised ML.** 

Generally, you can combine parts from the individual assignments and use them as a template for the module assignment. Going beyond that is not required (but for sure appreciated). Below a (rather detailed) checklist to make sure you have all the pieces.  
- Definition of a problem statement and a short outline of the implementation  
- Description of data acquisition / how it was collected (by you or the publisher of the data)
- Data preparation 
    - Data cleaning (if needed) 
    - Recoding (label encoding, dummy creation etc.) 
    - Merging and wrangling (if needed) 
- Exploratory data analysis  
    - Relevant! summary statistics  
    - Relevant! visualisations  
    - Appropriate description (This is important!)  
    - Optional! unsupervised machine learning for EDA or SML preprocessing (eg. dimensionality reduction, clustering)
- Feature scaling (if applicable)  
- Missing data handing (dropping or inputing) 
- Supervised ML  
    - Train- / Testset preparation  
    - classification or/and regression problem  
    - Use of different algorithms (min. 3) compared and ranked according to their performance  
    - using appropriate metrics (k-fold cross-validation)  
    - you may include hyperparameter tuning (grid-search, adaptive resampling etc.)  
    - performance evaluation on the test set (scores, performance reports but also visuals where useful) 

**Many of the steps are optional**. So choose which methods you deem helpful and relevant to explore your chosen problem. 


**Note:** Quality > Quantity. Consider which analysis, summarization, and visualization adds value. Excessive and unselective outputs (e.g. running 20 different models without providing a reason for, providing all possibilities of different plots without discussing and evaluating the insights gained from it) will not be considered helpful but rather distracting. 

### Documentation and Deliverables

You are asked to hand in a **well commented functional computational notebook**


#### Computational Notebook

The notebook targets a machine-learning literate audience. Here you can go deeper into the technical details and method considerations. Provide thorough documentation of the whole process, the used methods. Describe the intuition behind the selected and used methods, justify choices made, and interpret results (e.g. Why scaling? Why splitting the data? Why certain tabulations and visualizations? What can be seen from ... ?, How did you select a particular algorithm? Why did you scale features in one way or another?).  

Please provide the notebook as a PDF.

<!---
## Finally

-   Submission deadline is **27.09** - on [https://digitaleksamen.aau.dk/](https://digitaleksamen.aau.dk/)
-   Write to the secretary about your groups and language choice
--->
-  In case of trouble/issues/questions, please write on Teams.
