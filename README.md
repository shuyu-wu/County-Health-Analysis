# County-Health-Analysis

## Introduction

In this project we will investigate an Health Dataset containing Counties data from USA for 2019

## Objectives

* Analyze and perform EDA on the Dataset
* Applying knowledge of CRISP-DM methodology
* Answering 2 questions (1 from Shuyu and 1 from Marc)

<img src='https://www.researchgate.net/profile/Klemen_Kenda/publication/320100474/figure/fig1/AS:614088057040898@1523421410342/Cross-Industry-Standard-Process-for-Data-Mining-CRISP-DM-12.png' width="250" height="250">

### Final Project Summary
For this project we investigated the Health Dataset coming from a collaboration between the Robert Wood Johnson Foundation and the University of Wisconsin Population Health Institute.
We applied our knowledge of the CRISP-DM methodology to investigate the dataset.
We applied our previous knowledge of cleaning, EDA, dropping features based on correlations and p-values in order to prepare our dataset for modeling.
We used feature engineering (interactions and polynomials) to build better predictors for our targets.
Finally we scaled our features and run Ridge, Lasso, Elastic models using cross validation technique.

#### Question 1
* Can we help an Insurance company know the important factors predicting life expectancy in USA?

#### Question 2
* What are the most significant features for causing insufficient sleep?

<img src='https://github.com/locsta/County-Health-Analysis/blob/master/Pictures/Findings%20Banner.png'>

#### Question 1 **findings**
We were able to know that the 3 most important factors on Life Expectancy are:
* Diabetes (negative impact)
* Household Income (positive impact)
* Food Insecure (negative impact)

##### Heatmap of USA Life Expectancy
- The darker the shorter the life expectancy is
<img src='https://github.com/locsta/County-Health-Analysis/blob/master/Pictures/USA%20Life%20Expectancy.png'>

#### Question 2 **findings**
We were able to know that the 3 most important factors on Rate of Insufficient sleep are:
* The 'Air quality PM2.5'
* The 'Excessive drinking'
* The '% Uninsured children'

##### Heatmap of USA Life Expectancy
- The darker the shorter the life expectancy is
<img src='https://github.com/locsta/County-Health-Analysis/blob/master/Pictures/USA%20Insufficient%20sleep%20rate.png'>

## Presentation
You can find our slides presentation here => [Slides presentation](https://docs.google.com/presentation/d/1DPYJGTTRfYLg3wpsMcjLd3zD0rRHiUP1HixzmOl4RX4/edit?ts=5e1dfb20#slide=id.p)

