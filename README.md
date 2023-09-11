Before classification of text sentiment, the plain text documents need to be transformed into features for machine learning classification of the sentiments as positive or negative. I have compared 3 features extraction techniques in the IMDb dataset which are bag of Words, TF-IDF(Term Frequency - Inverse Document Frequency) and trigram. Post this feature extraction, I used logistic regression as a machine learning approach to predict the sentiment is postive or negative. The input to this logistic regression was the features selected from each of the feature selection techniques(BoW, Trigram and TF-IDF). The accuracy and F1 score was calculated for all the three. It showed TF-IDF was the best feature extraction technique.

<img width="172" alt="image" src="https://github.com/Soham2oo4/GDSC_Shortlist_Task/assets/122992973/36f07ef1-9cb5-490f-9b88-7728982faf9a">


I have also applied machine learning approaches other that logistic regression which are Naive Bayes and SVM(Support Vector MAchine). For these machine learning techinques, I used features from the TF-IDF. Since we earlier found that TF-IDF is the best feature extraction technique. The results are shown below. 

Using Logistic regression (accuracy - 89% ; F1-score - 0.89). The below image displays the accuracy and the confusion matrix

<img width="291" alt="image" src="https://github.com/Soham2oo4/GDSC_Shortlist_Task/assets/122992973/88952478-f93b-4a1c-801a-581388af7580">

Using Support Vector Classifier (accuracy - 89.22% ; F1-score - 0.89).

<img width="275" alt="image" src="https://github.com/Soham2oo4/GDSC_Shortlist_Task/assets/122992973/31ff7a2a-11fa-476a-8809-e011574237c0">

Using Naive Bayes (accuracy - 86.44%% ; F1-score - 0.86).

<img width="293" alt="image" src="https://github.com/Soham2oo4/GDSC_Shortlist_Task/assets/122992973/a4c712c8-7adb-413c-9e39-adaf80615573">
