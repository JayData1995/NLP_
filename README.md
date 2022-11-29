# NLP
This project focuses on an area of supervised machine learning known as Natural Language Processing (NLP). The project makes use of text classification/regression which is one of the fundamental tasks in NLP to predict the acceptance score and review score of a corpus of Machine Learning (ML) peer review papers from the International Conference of Learning Representation (in the years between 2017 and 2020)

The ML models that were used
to perform the prediction were linear regression and support
vector machine (SVM). The systematic experimentation that
was performed was optimization of the SVM algorithm using
GridSearchCV. It was discovered that linear regression was not
the best ML model for predicting a binary categorical target
variable. It was also discovered that a SVM model which has
an imbalanced dataset, cannot be predicted with accuracy but
with f1 score. It was also discovered that a SVM classes with
low precision and recall would produce low f1 scores.
