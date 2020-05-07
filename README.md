# IMDB sentiment classification GPT2
IMDB sentiment classification with GPT2 pre training. The main file is [here](https://github.com/AminTaheri23/IMDB-sentiment-classification-GPT2/blob/master/transfer_learning_classification_GPT2.ipynb)

You can refresh your knowledge about GPT2 from [this awesome blog](http://jalammar.github.io/illustrated-gpt2/)

## Running in Google Colab
you can run a similar notebook in colab [from here ](https://colab.research.google.com/drive/1MgpwzojvoIRv8Fypxvy2OnjS-IiExlG3)

## We don't have CLS token!
what is a cls token? it is a token for classification. BERT has this token and it is retrieved from pooling and some other functions such as sigmoid, etc. it is not precisely said in the paper (if you found it please show me so i can edit this). some other folks on github found that it is ok to average each word vector to make and CLS token. so we are adapting to this approach here.

## Refrences
 - [Base notebook]( https://github.com/jalammar/jalammar.github.io/blob/master/notebooks/bert/A_Visual_Notebook_to_Using_BERT_for_the_First_Time.ipynb)

- [imdb without training](https://machinelearningmastery.com/predict-sentiment-movie-reviews-using-deep-learning/)

- [gpt 2 docs from hugging face (and it's pre train)](https://huggingface.co/transformers/model_doc/gpt2.html)

- [kaggle data sets from](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

- [jay alammar blog for visualizing gpt2](http://jalammar.github.io/illustrated-gpt2/)

- a stack overflow to remove html tags from the data set
