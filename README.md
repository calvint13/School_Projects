# These are school projects done in the Nait Data Analytics Program

## Assignment 2 - Regression

Predict the TOTAL COMPENSATION for this year
In this assignment, I predicted the total compensation for tech workers in Europe based on the details of their work using the provided salary survey data.

Process and Steps
Data Preparation:

Constructed the total compensation by combining the columns "Yearly brutto salary (without bonus and stocks) in EUR" and "Yearly bonus + stocks in EUR".
Addressed categorical variables with many unique values and small counts to avoid creating columns with many zeros.
Imputed missing data and performed necessary data manipulations.
Model Training:

Experimented with various regression methods, including ExtraTreesRegressor.
Initially, the model accuracy was low with large errors and a low R2 score, indicating room for optimization.
Optimization and Tuning:

Conducted exploratory data analysis (EDA) and iterative data cleaning.
Explored feature selection methods and hyperparameter tuning using Grid Search.
Investigated the use of TransformedTargetRegressor to handle skewed target distributions.
Code Organization:

Ensured the code runs with "RUN ALL", loading the data, processing it, and generating results.
Cleaned up the code by commenting out or removing redundant steps.


Sure, here's the revised version for an individual project:

## Assignment 4 - Simple Neural Networks

In this assignment, I tackled the realistic task of predicting fraud from transaction data using simple neural networks.

Process and Steps
Handling Imbalanced Data:

Addressed the imbalance in the dataset. Referenced ideas from the TensorFlow tutorial on imbalanced data.
Data Preparation:

Transformed locations, time, and date of birth (dob) into more useful representations. Although these features are not very useful on their own, I made them more informative with minimal code.
Ensured there were no missing rows, making data preparation the primary focus.
Model Training:

Built and trained simple neural network models to predict fraud from the transaction data.
Utilized the large number of rows to handle a reasonably wide dataset effectively.
Optimization and Evaluation:

Experimented with different neural network architectures and hyperparameters.
Evaluated model performance using appropriate metrics and techniques to handle imbalanced data.

## Project 1 - NLP and Text Classification

In this project, we (group of 3) classified some angry comments into their respective categories of anger. The process we followed was roughly:

We used NLP techniques to process the training data.
We trained models to predict which class(es) each comment belongs to.
A comment can belong to any number of classes, including none.
We generated predictions for each of the comments in the test data.
We wrote our test data predictions to a CSV file, which was then scored.
We used various models and NLP libraries. We thought about the problem, looked back to see if there was anything that might help, gave it a try, and observed the results. We regularly referred to a "toolkit" of techniques, not knowing which ones we'd need, but aimed for a simple goal: if it made the predictions more accurate, it was helpful. There wasn't one specific solution; there were many potential approaches.


## Project 2 - Veggie Classification

In this assignment, we (group of 3) classified images of vegetables.

Parts
We performed two separate classifications:

First, we created a model from scratch.
Then, we used transfer learning with a pretrained model of our choice, adapted to this data.
There wasn't an explicit evaluation of accuracy, but we took steps to make each model as accurate as we reasonably could, using any tuning options available. Additionally, we structured our work into a well-organized and clear notebook that explained what we did and found. We considered the following elements:

Sections and headings.
A description of the approach taken (e.g., what we did to determine size, tune, evaluate, etc.).
Visualization of important aspects such as a confusion matrix and some images.
Results, mainly focused on the scoring of the test data.


