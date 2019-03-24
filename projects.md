---
title: Projects
layout: default
published: true
---


# Project List
_[My First Kaggle Competition: Elo Merchant Category Recommendation](https://www.kaggle.com/c/elo-merchant-category-recommendation)_ – 
: For my Capstone Project I decided to take part in a Kaggle competition: a competition hosted by Elo (a Brazilian payments company) to predict customer loyalty scores for each credit card user. The crux of the regression problem was that 1% of the scores were extreme outliers with the same value, swaying the RMSE metric. Due to the score being ill-defined and Elo’s agenda not being clear, the competition was seen as very difficult.

My approach was to carefully deliberate in pre-processing, and to try and reverse engineer the shape-parameters of the purchase amounts and the target which had been obfuscated. I spent the majority of my time feature engineering, contriving 1000+ features from 31 million transactions. I tried to read all the threads and papers on the subject to understand models used in loyalty scores such as Pareto/NBD.

It was important to create a good CV framework and trust in it rather than the public leaderboard score. During the project I used an optimization procedure to find the shape parameters of the target and purchase amount. I used feature elimination based on Boruta and field aware factorization machines. My model pipeline comprised three models, using both an LGboost regressor and classifier.

I found the competition a rewarding experience, and being part of a community who share information raised the level hugely. 
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
<br/>  
  
Predicting Data Science salaries from the job Description, Flask web application – *December, 2018*
: This is a web scraping and natural language processing project. Many Data Science job descriptions omit the salary, which to most, definitely ranks as a top criterion!
Are those on the job hunt supposed to be demure and welcome asymmetric information? Inferring the salary as best they can, and go through the whole application process, only to find out at the end. This is time-consuming, let alone difficult if the specific role is niche or is in a new field. A web application link will follow where HR and job searchers in Data Science can copy and paste the description in a text-box, for a salary estimation to be then produced. Perhaps some description authors will use the model to deliberately bely true salaries down the line…


```
– Web scraping from Indeed, Glassdoor etc.
— Trained on UK Data Science job decriptions
— Location & Title are important features
— Basic NLP techniques — vectorizers
— Model Tuning
— Web app development 
```  
<br/>  
   
_[Multiple Linear Regression on the Ames housing data](https://github.com/jordiclive/MLR/blob/master/MLR.ipynb)_ – *November, 2018*
: An exercise in predicting the sale price of residential properties based on their ‘fixed characteristics’ using *multiple linear regression* with regularization. Then a secondary model is built with the unfixed features, in order to attempt to account for the reducible error of the first. This would be of interest to property developers.

<img src="{{site.baseurl}}/Screen Shot 2019-01-31 at 12.38.57.png" alt="regularization_path" width="400"/> 

  
```
— Feature Selection
— Regularization paths
— Residual Analysis 
```
<br/>



## Small Projects

_[Take-home exercise for Revolut: Data Science & Problem-solving](https://github.com/jordiclive/Revolut_KYC_Exercise/blob/master/KYC_challenge.pdf)_ – *2018*
: Mostly work with *pandas* and *matplotlib* to investigate changes in [*Revolut’s*](https://en.wikipedia.org/wiki/Revolut) Know your customer (KYC) pass rates for onboarding. In additon, I produced a [written report](https://github.com/jordiclive/Revolut_KYC_Exercise/blob/master/JClive_Report_Ops_Challenge.pdf) interpreting the analysis.


_[The Guardian & The Observer crossword](https://github.com/jordiclive/The_Guardian_crossword)_ – *2016*
: Simple code to redirect to the current crossword of the day. My father has a ritual of completing this particular crossword at lunch-time every day. This expedites that ritual, by saving one click. As well as avoiding the weekly confusion each Sunday when there is no *Guardian* Quick, but a Speedy in *The Observer* instead. Easy to run on Android, just **add-to-home-screen** this [link](https://jsfiddle.net/467Luazq/2).
