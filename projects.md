---
title: Projects
layout: default
published: true
---
### N.B.

Write-ups will appear.

Additionally, I am hoping to be a teaching assistant for the same data science course I am currently finishing, starting in [March](https://generalassemb.ly/education/data-science-immersive). I would lead full days, lecturing ML topics followed by guiding labs (usually undertaken in Jupyter Notebooks), as well as provide assistance to students on a day-to-day basis. 

I believe this would be a good step for my development, preparing me for study and research in September 2019.


# Project List
_[My First Kaggle Competition: Elo Merchant Category Recommendation](https://www.kaggle.com/c/elo-merchant-category-recommendation)_ – *Ongoing, ends February 26th*
: I am currently 14th/3228 on the public LB—some ML techniques were required (I promise!). $50,000 prize money will be afforded to the top 5 entrants on the Private Leaderboard. 

<a href="https://www.kaggle.com/c/elo-merchant-category-recommendation/leaderboard">
  <img src="{{site.baseurl}}/Screen Shot 2019-01-31 at 10.59.30.png" alt="LB" width="1000"/> 
</a>

```
— EDA/Data Treatment
— Feature Engineering (1000+ features contrived from 31e6 transactions)
— Creating a good CV framework. Gradient boosting. SVMs.
— Feature Elimination based on Boruta
— Field-aware Factorization Machines
— Post-processing & Model Stacking
```




Predicting Data Science salaries from the job Description, Flask web application – *December, 2018*
: This is a web scraping and natural language processing project. Many Data Science job descriptions omit the salary, which to most definitely ranks as a top criteria!
Are those on the job hunt supposed to be demure and welcome asymmetric information? Inferring the salary as best they can, go through the application process only to find out at the end. This is time-consuming and can be difficult if the specific role is niche or is a new field. A web application link will follow where HR and job searchers in Data Science can copy and paste the description. Perhaps some job description authors will use the model to deliberately bely true salaries down the line…


```
– Web scraping from Indeed, Glassdoor etc.
— Trained on UK Data Science jobs
— Location & Title are important features
— Basic NLP techniques — vectorizers
— Model Tuning
— Web app development 
```




_[Multiple Linear Regression on Ames housing data](https://github.com/jordiclive/MLR/blob/master/MLR.ipynb)_ – *November, 2018*
: An exercise in predicting the sale price of residential properties based on their ‘fixed characteristics’ using *multiple linear Regression* with regularization. Then a secondary model is built with the unfixed features, in order to attempt to account for the reducible error of the first. This would be of interest to property developers.

<img src="{{site.baseurl}}/Screen Shot 2019-01-31 at 12.38.57.png" alt="regularization_path" width="400"/> 

  
```
— Feature Selection
— Regularization paths
— Residual Analysis and Variance
```




## Small Projects

Take-home exercise for Revolut: Data Science & Problem-solving  – *2018*
: Mostly work with *pandas* to investigate changes in Revolut’s Know your customer (KYC) pass rates for new customers. In additon, a report interpreting the analysis.


_[*The Guardian* & *The Observer* crossword](https://github.com/jordiclive/The_Guardian_crossword)_ – *2016*
: Simple code to redirect to the current crossword of the day. My father has a ritual of completing this particular crossword at lunch-time every day. This expedites that ritual, by saving one click, as well as avoiding the weekly confusion each Sunday when there is no Guardian quick crossword, but a Speedy Crossword in *The Observer*. Easy to run on Android, just *add-to-home-screen* this [link](https://jsfiddle.net/467Luazq/2).
