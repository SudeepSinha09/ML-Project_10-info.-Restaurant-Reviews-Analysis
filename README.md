# ML-Project_10-info.-Restaurant-Reviews-Analysis
### Data Details 

  Kaggle - https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews
  Colab Notebook - https://colab.research.google.com/drive/1IcJqSIa0pZUzNYzQJzN72QKfGu9yc3Ng?usp=sharing
  
#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_10-info.-Restaurant-Reviews-Analysis/blob/main/Restaurant%20Reviews%20Analysis.ipynb

## Description

This Dataset contains two rows Customer Reviews and Liked.
Customer reviews tells us about the reviews given by the customers for a food in restaurant and liked column tells about whether they liked the food or not.

## An Overview of EDA

![image](https://user-images.githubusercontent.com/93086122/210540774-4e53175c-a917-4043-a6e3-69ae5351f0db.png)

## Project Brief

In this project, we aimed to build a machine learning model to analyze customer reviews of restaurants. The goal was to classify the reviews as positive or negative based on the customer's experience at the restaurant. Understanding customer sentiment is important for restaurants as it can help them identify areas of strength and improvement.

To build the classification model, we collected customer reviews of restaurants from various sources and pre-processed the data to prepare it for modeling. We then split the data into a training set and a test set to evaluate the models.

We evaluated several different machine learning models for the task, including XGBoost classifier and GaussianNB classifier. We trained each model using the training data and evaluated their performance on the test data using various evaluation metrics, including accuracy.

Comparing the accuracy values for all the models, we found that the GaussianNB classifier was the most accurate, with an accuracy of approximately 73.0% in classifying the customer reviews as positive or negative. Based on this, we selected the GaussianNB classifier as the final model for the restaurant review analysis.

Overall, this project helped us develop a model that can accurately classify customer reviews of restaurants based on their sentiment, enabling restaurants to gain valuable insights into their customers' experiences.

##### The model selected - XGBoost classifier
