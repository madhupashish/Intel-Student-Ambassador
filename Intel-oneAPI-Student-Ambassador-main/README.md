# EPL match prediction

![epl](https://github.com/Utsabab/Intel-oneAPI-Student-Ambassador/assets/9398288/76043ac7-4a7e-4cbe-80cd-ecd0cbf8ba93)

## Overview

Welcome to the English Premier League (EPL) Match Result Prediction Project! This project was created as part of my application for the Intel Student Ambassador position. In this project, I have implemented three different classification algorithms - K-Nearest Neighbors (KNN), Naive Bayes, and Decision Trees - to predict the outcomes of EPL matches.

## Project Goals

The main objective of this project is to explore the effectiveness of these machine learning classifiers in predicting EPL match results. By analyzing historical data and using various features such as team statistics, player performance, and match circumstances, we aim to determine which classifier yields the most accurate predictions.

## Why EPL Match Prediction?

Predicting the outcomes of EPL matches is not only an exciting application of machine learning but also has practical implications in sports analytics and betting. It involves a blend of data analysis, feature engineering, and model evaluation, making it an ideal project to showcase my skills and passion for machine learning.

## Project Structure

* Data collection: The data provides information on games from seasons 21/22 and 22/23. The features include ['date', 'time', 'comp', 'round', 'day', 'venue', 'result', 'gf', 'ga','opponent', 'xg', 'xga', 'poss', 'attendance', 'captain', 'formation','referee', 'sh', 'sot', 'dist', 'fk', 'pk', 'pkatt', 'season', 'team'] where 'result' is the target label. 
  
* Preprocessing: Data preprocessing includes cleaning, finding missing values, replacing missing numerical values with median values, categorizing, label encoding, normalizing, and target label balancing using SMOTE for model training.

![Unbalanced](https://github.com/Utsabab/Intel-oneAPI-Student-Ambassador/assets/9398288/d5379f9c-122c-47b1-835e-c256d492a30f)

![balanced](https://github.com/Utsabab/Intel-oneAPI-Student-Ambassador/assets/9398288/f659118d-513c-4cc2-802a-983d6fe54479)

* Model Implementation: We implement KNN, Naive Bayes, and Decision Tree classifiers.

* Evaluation: Each model's performance is evaluated using accuracy.

* Comparison: We compare the models to determine which one performs the best in predicting EPL match results.

* Documentation: The project is well-documented, including code comments and explanations to help others understand and replicate the work.

## Intel oneAPI

With Intel(R) Extension for Scikit-learn you can accelerate your Scikit-learn applications and still have full conformance with all Scikit-Learn APIs and algorithms. This is a free software AI accelerator that brings over 10-100X acceleration across a variety of applications. And you do not even need to change the existing code!

## Result

![result](https://github.com/Utsabab/Intel-oneAPI-Student-Ambassador/assets/9398288/3c8d2779-f7ff-4f74-b512-80853f5a7793)

## Dependencies

* Python
* Scikit-lean
* Intelex
* Pandas
* Matplotlib
* Seaborn

## How to use?

Download the notebook and run it in your favorite IDE for ML. 

## Conclusion

I hope you find this project insightful and informative. Feel free to explore the code, dataset, and documentation to better understand the process and results of predicting EPL match outcomes using machine learning.

If you have any questions, suggestions, or feedback, please don't hesitate to reach out.

Thank you for visiting this repository!
