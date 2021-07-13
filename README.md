# Red-Wine-Quality
This repository holds the code and the data for the Red Wine Quality project

## Motivation
In this project, we will explore a wine quality dataset. The objective is to answer to 3 interesting questions that will hopefully help wine manufacturers make certain decisions. The questions are the following:

- Is there a correlation between alcohol and quality? This question is interesting because it can be used by wine manufacturers to produce wines low in alcohol if the quality did not drop dramatically.
- Can we predict pH based on fixed acidity, volatile acidity, and citric acid?
- Can we predict quality based on all the given parameters of the dataset?

## Data
The data used in this project is the Red Wine Quality dataset which can be found either in this repository or following this link: https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009

## Files in the repository
- red_wine_quality.ipynb - The jupyter notebook containing the code
- winequality-red.csv -  The csv file containing the wine quality dataset

## Libraries used
- Pandas
- Numpy
- Seaborn
- Scikit-learn

## Results
- The correlation between alcohol and quality is not statistically significant to state that the more alcohol the wine has, the better the quality. However, we cannot say the opposite either. Meaning that we still cannot say that lower alcohol will result in better quality either.
- It is not possible to predict pH based just on fixed acidity, volatile acidity, and citric acid. Our intuition might say that we would need other parameters such as residual sugar or chlorides to make a more accurate prediction.
- We cannot predict quality accurately with the given parameters of the dataset.

## Blog Post
I have also created a post in Medium where I explain my working in analysing this dataset. The post can be found in the following link: https://ariehlevyp.medium.com/red-wine-quality-b878f5d5f143
