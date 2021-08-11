# Building NLP Web Apps With Gradio And Hugging Face Transformers

![](https://miro.medium.com/max/1400/1*DHsXieocan8E6ntk-8O8WQ.gif)

This series of notebooks is aimed at helping fellow NLP/ML enthusiasts quickly build web apps using the Gradio and transformers libraries.

## 1A: SENTIMENT-ANALYSIS APP
[Notebook1.0](https://github.com/chuachinhon/gradio_nlp/blob/main/notebooks/1.0_gradio_sentiment.ipynb): I start with one of the simplest examples possible — building a web app for sentiment analysis using Hugging Face’s pipeline API.


## 1B: TROLL TWEET DETECTOR APP
![](https://miro.medium.com/max/2000/1*7nPox8VyxnmcBNTRG3Pcvg.png)

[Notebook1.1](https://github.com/chuachinhon/gradio_nlp/blob/main/notebooks/1.1_gradio_logreg.ipynb): Gradio works just as well with pickled models via scikit-learn and joblib. This notebook demos a quick deployment of a trained Logistic Regression classifier for troll-Vs-real tweets.


## 2: DEPLOY MODELS IN 'PARALLEL'
![](https://miro.medium.com/max/2000/1*YUBqz6xteSNKzS4UNMQglQ.png)

[Notebook2.0](https://github.com/chuachinhon/gradio_nlp/blob/main/notebooks/2.0_gradio_parallel_summaries.ipynb): Demo web app to compare the summarization capabilities of two different models: FB’s Bart and Google’s Pegasus. This is a great way to directly compare the results from multiple models without having to copy out the results from different apps, or switch screens back and forth between two models.


## 3: DEPLOY MODELS IN 'SERIES'
![](https://miro.medium.com/max/2000/1*yw8KlonkN9GlwLwWSh0TgA.png)

[Notebook3.0](https://github.com/chuachinhon/gradio_nlp/blob/main/notebooks/3.0_gradio_series.ipynb): Demo web app for connecting models of different functionalities under one Gradio app, in this case a translator-summarizer that takes in Chinese text and produces a summary of the English translation.


## 4: 'MIXED-MEDIA' APP
![](https://miro.medium.com/max/2000/1*8e6d27yEOvKZxRb_ECbtBA.png)

[Notebook4.0](https://github.com/chuachinhon/gradio_nlp/blob/main/notebooks/4.0_gradio_audio_text.ipynb): Demo speech-to-text app that takes in audio clips and returns a text transcript.


# MEDIUM

More details in this [Medium post](https://chuachinhon.medium.com/building-nlp-web-apps-with-gradio-and-hugging-face-transformers-59ce8ab4a319).


---
