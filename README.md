# ML_SMS_Spam_classifier
The project can detect if the sms is spam or not

The webpage looks like the below image
![image](https://github.com/yugaljindal/ML_SMS_Spam_classifier/assets/43234658/92dcb889-02a6-41f3-9f60-ad084fb14e43)

The message are detected like the below image example

![image](https://github.com/yugaljindal/ML_SMS_Spam_classifier/assets/43234658/67920599-4d5e-4f1e-802e-23b80090bf23)
![image](https://github.com/yugaljindal/ML_SMS_Spam_classifier/assets/43234658/0109a194-05a4-41c9-b07e-97d6840113d4)

The accuracy score and precision of our model looks like:

![image](https://github.com/yugaljindal/ML_SMS_Spam_classifier/assets/43234658/f082f3d7-3009-4989-8122-0996a2201612)



How the project is implemented:
The SMS Spam collection dataset is taken from kaggle.
The data is preprocessed
EDA is performed
Model is trained - We are using Naive Bayes as it is giving good precision_score and accuracy_score
Using pickle we generated two files model.pkl and vectorizer.pkl
The generated pickle files are loaded and using streamlit we created a simple webpage from our trained model.
