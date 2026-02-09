# clustering-dimension-reduction-global-development-indicators
Clustering and Dimensionality Reduction of Global Development Indicators Project in Python

Project Overview 
This project applies unsupervised learning techniques to analyze and group countries based on multidimensional development indicators published by the World Bank. The goal is to identify clusters of countries with similar development profiles and to understand which dimensions of development contribute most strongly to these groupings.

The analysis combines clustering and dimensionality reduction methods, making it particularly relevant for exploratory data analysis and policy-oriented data science applications.

Motivation
An existing compiled dataset of development indicators was initially considered. However, it lacked sufficient documentation on data sources and data generation processes, making it difficult to properly assess reliability and reproducibility.
To ensure data transparency, consistency, and methodological soundness, the dataset was therefore constructed independently using officially published indicators from the World Bank World Development Indicators (WDI) database.

Data Collection & Construction
* Source: World Bank – World Development Indicators
* Reference year: 2022 Selected because it is both recent and exhibits the lowest proportion of missing values across indicators. 
 
Indicator Categories
The final dataset includes indicators spanning multiple development dimensions, including: 
* Health outcomes
* Policy and institutional performance 
* Natural and economic resource indicators

Several additional indicators (e.g., Gini index, Official Development Assistance) were evaluated but ultimately excluded due to excessive missingness across countries, which would have significantly reduced global coverage. Considerable effort was devoted to balancing indicator richness with country coverage, ensuring the dataset remained both informative and comparable. 

Objectives

The primary objectives of this project are to:
* Group countries based on multidimensional development indicators using unsupervised learning
* Identify clusters of countries with similar development profiles
* Explore latent structures in the data via dimensionality reduction
* Analyze feature contributions to better understand which development dimensions drive observed groupings
* Provide insights relevant to economic development, policy analysis, and international assistance

Methods (High-Level):

* Data preprocessing and standardization
* Clustering techniques (PAM, k-means, hierarchical clustering)
* Dimensionality reduction (ePCA)
* Cluster interpretation and visualization


Why This Project Matters

This project demonstrates practical skills in:

* Real-world data acquisition and cleaning
* Handling and manipulating data
* Unsupervised learning for exploratory analysis
* Translating statistical results into policy-relevant insights

How to use:
Either run all the cells of the .ipynb file, or open the .html file using a browser to see the results.
