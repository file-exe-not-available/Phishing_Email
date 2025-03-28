The ipynb file is the main model that is trained using the Phishing_Email dataset from kaggle. 
The model is saved as Phishing.joblib and the tfidf is a vectorizer that converts the string to numerical values for the model.

The file takes an input, which is the contents of the email and makes a prediction about whether it is phishing or safe. 

The accuracy of the logistic regression model is 96.7%

FUTURE TODO: 
  Might create a frontend that scans the page instead of taking a text input.
