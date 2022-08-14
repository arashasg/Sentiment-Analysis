# Sentiment-Analysis

In this repository, we applied two models to classify the sentiment of the text.
##### Preprocessing
One to three annotators annotated each news story in the dataset as positive, neutral, or negative. Some of the news stories were annotated by two, and the labels were different, so we decided not to include them in our final dataset and reannotate them later. Additionally, we deleted multiple newlines and tabs in the news stories and replaced them with space. Finally, we normalized all the words in the dataset.

##### Models
I have implemented two models. One of them classifies the sentiments using a pre-trained Bert model in the Persian language, which I fine-tuned for my sentiment classification task, and the other is an RNN-based deep learning model I trained from scratch. 

##### Dataset
Dataset is crawled from Persian news websites and was annotated by students of NLP course in sharif university of technology under the supervision of prof. [Ehsan Asgari](https://scholar.google.com/citations?user=lIVvIFsAAAAJ&hl=en).

Further explanations are available in the notebooks.

