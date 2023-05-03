# Hate Speech Detection  
## Synopsis:  
Performs classification of tweets into positive and negative (racist/sexist) using RoBERTa model of Tranformers library; compared with classification results from other classifiers  
## Pipeline of the ML model:  
### *Data Pre-processing:*  
Data exploration followed by data visualization in the form of graphs and plots and WordClouds. Data Cleaning using NLTK library.    
### *RoBERTa model:*  
Encoding the sentences into id's and attention masks using RoBERTa tokeniser. Creating the RoBERTa model by adding the additional layers to the existing imported model. Fitting the cleaned tweets to this model and getting the predictions. Evaluating our results using ROC scores and Accuracy.  
### *Alternative models:*  
Cleaning the original model followed by vectorisation using TFiDF vectoriser. SMOTE application to balance the skewed data. Classification using Logistic Regression, Naive Bayes Classfier, Random Forest Classifier and SVM  
