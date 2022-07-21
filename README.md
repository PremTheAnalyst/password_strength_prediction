# password_strength_prediction
Predicted the strength of password using NLP and ML ,using a dataset from Kaggle.<br  />
I used TfidfVectorizer from feature_extraction.text. <br  />
To avoid Parse Error i used error_bad_lines=False.<br  />
We have two columns password and strength.Values in strength column are 0,1,2 . 0 being the least safe,1 is safer and 2 is the safest password.<br  />
By using NLP i will predict whether a password falls in category 0,1 or 2.
