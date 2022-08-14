# Sentiment-Analysis

In this repository, we applied two models to classify the sentiment of the text.
##### Preprocessing
One to three annotators annotated each news story in the dataset as positive, neutral, or negative. Some of the news stories were annotated by two, and the labels were different, so we decided not to include them in our final dataset and reannotate them later. Additionally, we deleted multiple newlines and tabs in the news stories and replaced them with space. Finally, we normalized all the words in the dataset.

##### Models
I have implemented two models. One of them classifies the sentiments using a pre-trained Bert model in the Persian language, which I fine-tuned for my sentiment classification task, and the other is an RNN-based deep learning model I trained from scratch. 

***sample input:***

```
تداوم بی رونقی بازارهای داخلی. همراه با کاهش نرخ بازده اوراق قرضه ایالات متحده آمریکا، طلا توانست بار دیگر صعودی شده و در روز جمعه حتی تا نزدیکی 1780 دلار نیز صعود کرده و در نهایت، بهای هر اونس طلا در آخرین روز معاملاتی بازار جهانی۱0 دلار و 1۰ سنت معادل 6/ 0 درصد افزایش یافت و در ۱۷76 دلار و 9۰ سنت بسته شد که بالاترین قیمت از ۲۴ فوریه بود. پس از اینکه قیمت طلا سطح مقاومتی مهم ۱۷۶۵ دلار را شکست و در بالاترین حد دو ماه گذشته قرار گرفت، تحلیلگران به روند افزایشی طلا در معاملات هفته جاری بی نهایت خوش بین شدند و بر این باورند که طلا می تواند سطح روانی 1800 دلار را به دست آورده و صعود های بیشتری از خود نشان دهد.

```
***sample output:***
![Negative](https://github.com/arashasg/sentiment-analysis/blob/main/img/image.jpg?raw=true)

The rows of the plot represent the probability that the news story is negative, neutral, and positive, respectively.

##### Dataset
Dataset is crawled from Persian news websites and was annotated by students of NLP course in sharif university of technology under the supervision of prof. [Ehsan Asgari](https://scholar.google.com/citations?user=lIVvIFsAAAAJ&hl=en).


Further explanations are available in the notebooks.

