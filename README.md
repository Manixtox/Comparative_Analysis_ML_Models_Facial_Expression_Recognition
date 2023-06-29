# Comparative_Analysis_ML_Models_Facial_Expression_Recognition
A PRECISION COMPARATIVE ANALYSIS OF DIFFERENT MACHINE LEARNING AND DEEP LEARNING MODELS FOR THE PREDICTION OF FACIAL EXPRESSION

INTRODUCTION

Facial expression is one of the most important forms of non-verbal communication, it is a way in which humans exchange information that tells us about the mood of our peers. In the field of Computer Vision there are many applications for the recognition of facial expression, "FER", for its acronym in English. As examples we have: Man/Machine Interaction, Biometrics, Customer Satisfaction, Smart Medicine, etc.

However high intra -class variation and low inter -class variation make FER a very challenging problem in the field of Computer Vision ( Saeed , et al. 2018). Normally, this based on social interactions, facial expressions can be classified into: happiness, sadness, anger, fright, surprise, disgust and finally we can also add the "neutral" expression.

Most of the recent studies focus on solving this problem using CNNs ( Convolutional Neural Networks). Many of the studies focus on algorithms to extract better attributes. Example: Gabor filter or an RBF network . ( Karkra . 2016).

In this work we use a selection of three Machine Learning models and a couple of Deep Learning Network models to predict facial expression using the FER2013 Dataset , available on Kaggle . We made special emphasis on the use of VGG16 for attribute extraction, and finally VGG16 with Data Augmentation for attribute extraction and prediction. We will compare results at the end.
