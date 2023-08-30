---
title: "Breast cancer prediction by ensemble meta-feature space generator based on deep neural network"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
date: 2023-08-29
venue: 'Biomedical Signal Processing and Control'
paperurl: 'https://doi.org/10.1016/j.bspc.2023.105382'
citation: 'Taheri, M., & Omranpour, H. (2024). Breast cancer prediction by ensemble meta-feature space generator based on deep neural network. Biomedical Signal Processing and Control, 87, 105382.'
---
Background: Classifying ultrasound images is one of the quickest approaches to diagnose breast cancer. In recent
years, the medical community has increasingly turned to deep learning-based methods, which have demon­
strated superior performance compared to other existing methods for most computer vision tasks. Since deep
learning approaches suffer from over-fitting problem, the main challenge in the medical image analysis is the
lack of enough available dataset to train deep learning models to extract efficient features. Many existing
methods rely on data augmentation techniques to address the issue of over-fitting especially in imbalanced
datasets. However, the process of finding appropriate data augmentation methods often involves trial and error,
and it can be time-consuming. Therefore, there is a need to develop an algorithm that can automatically generate
effective features, and minimize the reliance on a large amount of data to overcome over-fitting.

Method: In this study, we introduced a novel ensemble meta-feature space generator (EMFSG-Net) for the clas­
sification of breast ultrasound images. We first employed a transfer learning approach to obtain initial features
from raw images. Then we applied our method to create a more efficient feature space from the initial features.
Our method is inspired by ensemble methods that aim to minimize bias and variance errors. Ensemble methods
are widely used in previous works based on classification models. The novelty of our approach is to adapt these
techniques to regression-based models, which enables us to construct a meta-feature generator capable of pro­
ducing an effective feature space. This method offers an effective solution to address the overfitting problem
commonly encountered in deep learning for medical image processing. By obtaining more suitable features, it
significantly improves the classification performance. Notably, this method eliminates the need for data
augmentation, which saves time by avoiding the search for appropriate data augmentation techniques. This
approach demonstrates its efficacy specifically in addressing imbalanced datasets, which are characterized by a
disproportionate distribution of class labels.
Result: We have evaluated our model on BUSI dataset, a collection of breast ultrasound images that is widely used
in scientific researches to detect breast cancer. We have achieved the accuracy of 97.96% and F1-score of 96.2%
on the dataset.

Conclusion: The experimental results show that the proposed model has increased 4.8% of the classification F1-
score compared to other feature extraction and deep learning methods.