---
title: "Papers"
permalink: /papers/
layout: single
author_profile: true
---

The following are research papers or project reports I've written for personal projects, projects for graduate coursework, or projects as part of a research team. They vary in style according to the requirements of the course or research advisor or my own whims. 
{: .text-justify}

### [Predicting Antidepressant Response with Electroencephalography](https://drewjohnston13.github.io/Predicting%20Antidepressant%20Response%20with%20Electroencephalography.pdf)
This paper endeavors to establish machine learning methods for predicting whether a
depressed patient will have a positive response to antidepressants. Outlined in the paper are efforts
to extract predictive features from electroencephalogram (EEG) signals of depressed patients and
use them to predict patient response. All data comes from the EMBARC dataset provided by the
National Institute of Mental Health Data Archive. Traditional machine learning models proved ineffective at predicting patient response from typical EEG features, but a recently developed machine
learning approach called SELSER gave promising results, predicting patient response with an accuracy of 78.9%.
{: .text-justify}

### [Innovative Features for Atrial Fibrillation Detection](https://drewjohnston13.github.io/atrial_fibrillation.pdf)
In this report, we present a new approach to atrial fibrillation (AF) detection. First, we
explore associated works detailing previous methods used to detect AF. We then provide summaries
of Physionet’s MIT-BIH Atrial Fibrillation Database and Computing in Cardiology Challenge 2017
Database and present results of our efforts to develop a robust model for detecting AF in electrocardiogram data using novel features based on RR intervals. Our contributions include a new feature
measuring irregularity of RR intervals and innovative applications of previous work to generate
novel features. Using a random forest classifier and 12 original features, we achieved accuracy of
0.963 and averaged F1-score of 0.962 with leave-one-person-out cross validation on the MIT-BIH
data. The same model achieved accuracy of 0.949 and averaged F1-score of 0.813 with 5-fold cross
validation on the 2017 Challenge data.
{: .text-justify}

### [A Stylometry-Based Book Recommendation System](https://drewjohnston13.github.io/book_recommender.pdf)
Recommendation systems are designed to connect consumers
to relevant products and information by personalizing recommendations
based on the consumers’ previous experiences. The vast majority of recommender systems use collaborative filtering methods that make recommendations based on the preferences of other users. This is often effective,
but has one major drawback: previously unrated items cannot be recommended by the system. Content-based recommender systems overcome this drawback by making suggestions based on inherent attributes of an
item. This paper describes a novel approach to content-based book recommendation using stylometry to compare the writing styles found in different books. A proof-of-concept model as been developed and tested, but the performance is difficult to evaluate due to the small size of thel ibrary that was developed. However, the system guarantees 100% coverage across the library and behaves as intended after empirical testing.
{: .text-justify}

### [Statistical Learning for Facial Demographic Analysis](https://drewjohnston13.github.io/morphIIpaper.pdf)
In this report, we explore the MORPH-II Dataset numerically and graphically. We
gather data on the demographics of the dataset then subset the data to train, test, and compare
various statistical learning models for classification and regression, including Polynomial Regression, Logistic Regression, Linear Discriminant Analysis (LDA), Quadratic Discriminant Analysis
(QDA), K-Nearest Neighbors (KNN), Decision Tree (DT), Bagging, Random Forest (RF), Boosting, and Support Vector Machine (SVM). Results for each model are compared; SVM achieved the
highest accuracy for gender classification, while Boosting attained the lowest mean squared error in
predicting age.
We further explore the use of Latent Class Analysis (LCA) as an unsupervised method for grouping individuals into classes based on chemical exposure. We conclude there is little to no relationship
between these classes and age or conviction status of each individual.
Finally, we return to age and gender prediction models and utilize Principal Component Analysis
(PCA) and Kernel PCA (KPCA) to reduce dimensionality and enable our models to train on a large
proportion of the data. Improvement is seen across all models.
{: .text-justify}

### [A Review of Pitchfork Music Reviews](https://drewjohnston13.github.io/A%20Review%20of%20Pitchfork%20Music%20Reviews.pdf)
_Pitchfork_, the self-proclaimed “Most Trusted Voice in Music,” wields great power and influence in the modern music community. The Chicago-based online magazine is one of the largest sites dedicated to publishing music reviews and ratings for both tracks and albums. In this paper, I describe my methods and results for detecting contrarian bias in _Pitchfork_ music reviews. I discuss my efforts toward collecting and cleaning the data, feature engineering, data visualization, and analysis. I conclude that there is evidence that _Pitchfork_ writers tend to favor certain niche genres, including "experimental" and "global" music. They also tend to favor new and different sounds over safer, more familiar musical expression. Albums with musical traits that are drastically different from the norm are more likely to receive higher scores and more likely to be awarded "Best New Music" by the music review company. 
{: .text-justify}

### [Optimal Control: Stabilizing a Double-Inverted Pendulum System](https://drewjohnston13.github.io/optimal_control.pdf)
In this paper, we outline our solution to the double inverted pendulum problem, wherein a double
pendulum is inverted and attached to a cart. The objective is to balance the double pendulum above the
cart by only exerting force on the cart. Our approach utilized the Linear Quadratic Regulator feedback
controller to exert optimal control on the cart and stabilize the system. We were successful in creating
a robust control system that balances the inverted double pendulum indefinitely regardless of initial
conditions on cart position or velocity, pendulum joint position or velocity, or pendulum tip position or
velocity.
{: .text-justify}
