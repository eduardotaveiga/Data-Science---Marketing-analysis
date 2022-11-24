[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<div class="alert alert-block alert-info">
<b><h2><center>Data Science Project - Marketing</center></h2></b>
</div>
Exploratory Data Analysis and Machine Learning for a marketing dataset.

This project is part of my data science learning journey. Feel free to send me a message regarding tips of any kind, like statistics, machine learning, visualizations, or even english grammar, I will be grateful. I hope that you find something useful here and learn with me too!

---
## Roadmap
*This work is currently in progress*
- [x] Exploratory Data Analysis
    - [x] Data cleaning
    - [x] Data analysis
- [x] Customer segmentation
    - [x] KMeans and PCA
    - [x] Cluster analysis
        - [x] Characteristics
        - [x] Consumption
- [x] Recommendations
- [x] Basic ML models 
    - [x] Evaluation
    - [x] Feature selection
    - [x] Model benchmark
    - [x] Hyperparameter tuning
    - [x] Predictions and SHAP values
- [ ] Model deployment
    - [ ] Web application using Dash
- [ ] Final report
---

## About the project

*Fictional background*

You are a Data Scientist hired by Company XYZ in order to help them in data-driven solutions since the CMO said that the recent marketing campaigns were not as effective as they expected. 

The company sells products divided in 6 major categories, Wines, Fruits, Meat, Fish, Sweet and Gold (rare/exotic products), through 3 different channels, physical stores, website and catalogs. Although the company's wealth is pretty solid, the profit growth perspectives for the next years aren't good, which justifies their initiatives along with the marketing department to increase sellings, mainly using Machine Learning and data oriented decisions.

The marketing department developed a new offer, and a pilot campaign was carried out with 2240 randomly selected customers, recording their responses and data, like demographics and behaviours. The CMO of Company XYZ said that the total cost of the new campaign was 6.72 million and the total revenue generated was 3.674 million. Also, the success of the campaign was 15%.

Hence, the CMO is looking for a predictive model that maximizes profits, picking the customers who are more likely to purchase the new offer, while leaving the non-respondents.

It's up to you to analyse the dataset aiming to provide a better understanding of the customer base, giving ideas to maximize profits, and develop a machine learning model to be applied on the rest of the customer base.

**Key concepts:**  
**Initial data preprocessing:** missing values, typo fixing, categorical to numeric encoding.  
**Exploratory Data Analysis:** data visualization with plotly, hypothesis testing, ANOVA, permutation test, posthoc test using Mann-Whitney U test.  
**Clusterization:** customer segmentation with KMeans and PCA, analysis and interpretation of each cluster.  
**Machine Learning evaluation:** false positives and false negatives, precion-recall, AUC.  
**Feature selection:** correlation, SelectKBest with chi2, Recursive Feature Extraction with linear model and tree based model.  
**Model benchmark:** train-test-split in unbalanced dataset, cross-validation with stratified KFold, scaling with StandardScaler and MinMaxScaler.    
**Hyperparameter tuning:** optuna, basic explanation of models and parameters, Underfitting.  
**Model selection:** precision-recall curve, threshold selection based on expected value structure.  
**Model predictions:** understanding model predictions with SHAP values.  

---
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


## Contact

Eduardo Veiga - [LinkedIn](https://www.linkedin.com/in/eduardo-veiga-0728221a6/)

Email - etaveiga@gmail.com

Project Link: [https://github.com/eduardotaveiga/Data-Science---Marketing-analysis](https://github.com/eduardotaveiga/Data-Science---Marketing-analysis)

## Acknowledgments
* Raw data: data.csv
* After EDA: ML_data.csv  
* The raw dataset is not mine. I got it from [this repository]
* See the *EDA and Segmentation* and *Machine Learning* notebooks for code detailed information!


[this repository]:https://github.com/nailson/ifood-data-business-analyst-test
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/eduardotaveiga/Data-Science---Marketing-analysis/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/eduardotaveiga/Data-Science---Marketing-analysis/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/eduardotaveiga/Data-Science---Marketing-analysis/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/eduardo-veiga-0728221a6/
