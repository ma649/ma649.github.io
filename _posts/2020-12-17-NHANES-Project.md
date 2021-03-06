---
published: true
layout: single
title: 'NHANES Project'
author_profile: true
read_time: true
categories: [projects]
toc: true
toc_sticky: true
sidebar:
    nav: sidebar-sample
header:
    teaser: "https://ma649.github.io/assets/images/NHANES-snippet.PNG"
---
The NHANES project is my thesis proposal for my Masters. Here is the abstract:

Recent success of statistical analysis and machine learning tools in the healthcare domain has prompted research into various areas of epidemi-
ology such as Cardiovascular Disease (CVD). Several obstacles however arise when dealing with large heterogeneous data such as bias, missing in-
formation and generalizability. To tackle these issues, we propose a five layer Deep Neural Network (DNN) using a Stochastic Gradient Descent
(SGD) optimizer to predict patients with cardiovascular disease using the NHANES datasets on various sample sizes. We also incorporate Pearson
correlation and Principle Component Analysis (PCA) to assess its usability nas a feature selection approach. Training our network on 146 features, our
optimum results are achieved on a sample size of 3,393 (2:1 class ratio) with a sensitivity of 70% and a specificity of 88%. These results were optimized
using a learning rate of η 0.01 and dropout rates of 0.3 and 0.6 respec- tively. This shows that our proposed method can obtain modest results 
when trained on small datasets. However, as the sample size increases, our DNN is unable to generalize and progressively obtains worse recall rates.


You can view the project on my [Github link](https://github.com/ma649/NHANES/blob/main/NHANESgit.ipynb)

![image](https://ma649.github.io/assets/images/NHANES-snippet.PNG)
