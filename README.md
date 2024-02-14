
## About this project
Quora is a question-and-answer website where users may ask questions and get
answers from other users. When a question is asked, Quora would use some methodology
to find a subset of its existing question data base such that this subset contains
questions which are “similar” to or about the same topic as the new question being
asked. Once this subset has been identified, Quora would employ a machine learning
technique to then determine if a duplicate question exists in this selected subset. <br>
- The problem of finding if two question pairs have the same meaning or not requires a
method to capture the semantic information and words vector features of questions
rather than just a group of words.
- This project aims to apply machine learning techniques to determine if any of the
question pairs is a duplicate.
- This relieves responders from answering repeated queries and directs users to the
most appropriate responses, thereby improving the overall user experience.
- This project uses SGDClassifier to implement both the linear classifiers logistic
regression and Support vector machine. The model behavior was
controlled with the loss parameter to make the SGDClassifier
perform as Logistic Regression - loss parameter was set to ‘log’ and to make the
SGDClassifier perform as SVM loss parameter was set to ‘hinge’. Each of these
methods were also calibrated using the Sklearn Calibration Classifier.
