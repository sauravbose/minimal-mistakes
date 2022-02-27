---
permalink: /projects/
title: "Projects"
author_profile: true
toc: true
toc_icon: "book"
---
*Last updated in December 2020.*
## Deep Learning

### Learning to detect rib fractures in chest X-rays
In this project detect rib fractures.

<center><img src="/images/DeepLearning/chest_xray.jpg"></center>

## Classical Machine Learning

### Personalized prediction of asthma persistence
[![](https://img.shields.io/badge/Adobe-Download_Paper-brightgreen?logo=Adobe%20Acrobat%20Reader)](/pdfs/Asthma_Plos.pdf)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/sauravbose/asthma-persistence-prediction)


In this NIH funded research project, we developed a machine learning solution to predict persistent asthma in school aged children using their EHR data. The analysis pipeline consisted of feature selection, class balance, Bayesian hyperparameter tuning and model evaluation. We achieved an ROC-AUC of 0.86 (95% precision, 82%
recall at 70% specificity) for our XGBoost model, demonstrating quantitative success of machine learning on a novel task. Further, we addressed clinical explainability needs by a qualitative audit of our model using permutation analysis. We found diagnosis age, race, prior diagnosis of allergic rhinitis, and eczema, health service utilization and prescription of Montelukast (an asthma controller medication) prior to age 5 years to be important predictors of asthma persistence.

This work was published in <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0247784" style="text-decoration: none;">PLoS One</a>

<center><img src="/images/ClassicalML/asthma.jpg"></center>

## Course Projects

### Characterizing Air Quality in Philadelphia
[![](https://img.shields.io/badge/RStudio-Open_Notebook-brightgreen?logo=RStudio)]({% post_url 2016-07-20-characterizing-air-quality %})

In this exploratory data analysis project, I studied the environmental (Air quality, Humidity, Noise Level and Temperature) conditions in the city of Philadelphia. For the analysis I scraped most of the data from the publicly available <a href="http://aircasting.habitatmap.org/mobile_map#?map_crowd=%22undefined%22&map=%7B%22zoom%22:5,%22lat%22:37.09024,%22lng%22:-95.712891,%22mapType%22:%22roadmap%22,%22hasChangedProgrammatically%22:false%7D&data=%7B%22sensorId%22:%22Particulate%20Matter-airbeam2-pm2.5%20(µg%2Fm³)%22,%22location%22:%22%22,%22tags%22:%22%22,%22usernames%22:%22%22,%22timeFrom%22:%221575936000%22,%22timeTo%22:%221607644799%22,%22heat%22:%7B%22lowest%22:0,%22low%22:12,%22mid%22:35,%22high%22:55,%22highest%22:150%7D,%22gridResolution%22:31,%22crowdMap%22:false%7D&fetchedSessionsCount=100" style="text-decoration: none;">AirCasting</a> database, collected some of my own using <a href="https://www.habitatmap.org/airbeamand" style="text-decoration: none;">AirBeam</a> sensors and leveraged Python's superior data munging and R's amazing visualization capabilities.

<center><img src="/images/CourseProjects/Aircasting.png" width="600"></center>

### Will Kobe make this shot?
[![](https://img.shields.io/badge/RStudio-Open_Notebook-brightgreen?logo=RStudio)]({% post_url 2017-12-15-Kobe %})

In this fun application of Machine Learning we used a publicly available dataset that contains all of Kobe Bryant’s 30,697 shots that he attempted over the course of his NBA career to answer two questions:
1. Can we predict the outcome of Kobe’s shot with reasonable accuracy?
2. What are the important parameters in determining the outcome of Kobe’s shot?

<center><img src="/images/CourseProjects/Kobe.png"></center>

### Predicting Readmission Probability for Diabetes Inpatients
[![](https://img.shields.io/badge/RStudio-Open_Notebook-brightgreen?logo=RStudio)]({% post_url 2017-10-15-Diabetes %})

In this predictive analytics project, we used a dataset made publicly available by the <a href="https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008" style="text-decoration: none;">Center for Clinical and Translational Research</a> at Virginia Commonwealth University to help better manage diabetes patients with a hospital admission. Our goals were two-fold:
1. Identify the factors determining whether or not the patient will be readmitted within 30 days.
2. Develop a classification model to predict if a patient will be readmitted within 30 days.

<center><img src="/images/CourseProjects/DiabetesReadmission.png" width="600"></center>

### Multi-class Classification of Tweets
[![](https://img.shields.io/badge/Adobe-Open Post-brightgreen?logo=Adobe%20Acrobat%20Reader)]({{ site.baseurl }}{% link _posts/Projects/2017-12-10-tweets.md %})

In a "classic course project" fashion, we explored the basics of Natural Language Processing to classify the sentiment of tweets.

<!-- Write something about the cost function being user-defined multi dimensional.  -->

<center><img src="/images/CourseProjects/TwitterMulticlass.png"></center>
