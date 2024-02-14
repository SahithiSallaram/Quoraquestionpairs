
## About this project
Quora, a popular question-and-answer website, employs a methodology to identify similar questions from its vast database when a new question is asked. Utilizing machine learning techniques, this project aims to enhance this process by automatically detecting duplicate question pairs. By predicting whether two questions have the same meaning, the project streamlines the user experience, prevents redundancy in responses, and directs users to the most relevant information.

## Project Overview
This project leverages a dataset containing pairs of questions from Quora. It preprocesses the questions using advanced techniques such as removing special characters, expanding contractions, and extracting features like TF-IDF vectors and fuzzy matching scores. Additionally, it employs machine learning models, including SGDClassifier with logistic regression and linear SVM, to classify duplicate question pairs.

## Objectives
- Semantic Understanding: Addressing the challenge of capturing semantic information and word vector features to determine the similarity between question pairs.
- Improved User Experience: By automating the detection of duplicate questions, the project enhances the overall user experience on Quora.
- Model Implementation: The project utilizes SGDClassifier to implement logistic regression and support vector machine (SVM) classifiers. The models are calibrated using Sklearn's Calibration Classifier to improve performance.
