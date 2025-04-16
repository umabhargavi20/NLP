# NLP
NLP text classfication with Disaster tweets
This project aims to classify tweets into disaster-related or non-disaster-related categories using natural language processing (NLP) techniques.

1.**Data Preprocessing:** 

Text Cleaning: Removing unwanted characters and formatting issues.

Stopword Removal: Eliminating common words that don't contribute much to the meaning.

Stemming: Reducing words to their base or root form.

Lemmatization: Converting words to their base or dictionary form, considering context.

**2.Feature Extraction**
   
TF-IDF (Term Frequency-Inverse Document Frequency): A statistical measure used to evaluate how important a word is to a document in a collection.

Word2Vec: A technique to compute vector representations of words, capturing semantic meanings.

**3. Model Training**
Logistic Regression: A linear model used for binary classification tasks.

Naive Bayes: A probabilistic classifier based on Bayes' theorem, assuming independence between features.

**4. Model Evaluation**
Accuracy: The proportion of correct predictions.

Precision, Recall, F1-Score: Metrics to evaluate the performance, especially in imbalanced datasets.

Confusion Matrix: A table to describe the performance of a classification model.

AUC-ROC Curve: A graphical representation of the trade-off between true positive rate and false positive rate.

**5. Prediction**
Final Model: The best-performing model is used to predict on new, unseen tweet data.
