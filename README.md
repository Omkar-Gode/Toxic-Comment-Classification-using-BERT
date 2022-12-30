# Toxic-Comment-Classification-using-BERT

Link to the Project - https://www.kaggle.com/code/omkarcgode/toxic-comment-classification-nlp-using-pytorch/notebook

* Toxic comment classification is a competition on kaggle in which we have to predict toxicity of a comment.
The link to the dataset - https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge

* The Dataset consists of 7 columns which are ID , comment text and 6 types of toxicity (toxic, severe toxic, insult, threat, obscene, identity hate). 

* The main task of the project is predict toxicity of a comment.

* Firstly, I Visualized the data and its distribution for the insights and to usnderstand which type of prediction task it actually is (ordinal, nominal).

* After the visualization, I cleaned the data using Regular Expressions. I removed hyperlinks, emojis, IP adresses, html/css elements, special characters and extra spaces from the comments. I didn't remove "stopwords" or didn't performed "stemming/lemmatization" because I used DistilBERT model which doesn't require these.

* Lastly, I used pretrained DistilBERTForSequenceClassification model for classfication and trained it on the data. I used Pytorch machine learning framework to train the model.

