 Message Spam Classifier
A machine learning–based web application that classifies text messages as Spam or Not Spam.
Built using Python, Scikit-learn, and Flask, and packaged for deployment (earlier via Heroku; now can be deployed on Render/Vercel/Any free alternative).

Features
✔️ Classifies SMS/text messages into Spam or Not Spam
✔️ Trained using TF-IDF + Naive Bayes / Logistic Regression
✔️ Simple Flask web interface
✔️ Model serialized using Pickle
✔️ Ready-to-deploy structure

 Model Workflow
1)Data Cleaning
2)Lowercasing
3)Removing punctuation, stopwords
4)Tokenization & stemming
5)Feature Extraction
6)TF-IDF Vectorizer
7)Training
8)Multinomial Naive Bayes / Logistic Regression
9)Evaluation

Accuracy, Precision, Confusion Matrix

Saving Artifacts

model.pkl

vectorizer.pkl
