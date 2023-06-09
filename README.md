# Transformers

A transformer is a deep learning model that adopts the mechanism of self-attention, differentially weighting the significance of each part of the input data. It is used primarily in the fields of natural language processing (NLP) and computer vision (CV).
Like recurrent neural networks (RNNs), transformers are designed to process sequential input data, such as natural language, with applications towards tasks such as translation and text summarization. 
However, unlike RNNs, transformers process the entire input all at once. The attention mechanism provides context for any position in the input sequence. For example, if the input data is a natural language sentence,
the transformer does not have to process one word at a time. This allows for more parallelization than RNNs and therefore reduces training times.
Transformers were introduced in 2017 by a team at Google Brain and are increasingly becoming the model of choice for NLP problems, replacing RNN models such as long short-term memory (LSTM). The additional training parallelization allows training on larger datasets.
This led to the development of pretrained systems such as BERT (Bidirectional Encoder Representations from Transformers) and GPT (Generative Pre-trained Transformer), which were trained with large language datasets, such as the Wikipedia Corpus and Common Crawl, and can be fine-tuned for specific tasks.

In recent years, the transformer model has become one of the main highlights of advances in deep learning and deep neural networks. It is mainly used for advanced applications in natural language processing. Google is using it to enhance its search engine results. 
OpenAI has used transformers to create its famous GPT-2 and GPT-3 models.

[<img target="_blank" src="https://user-images.githubusercontent.com/59423092/229551011-7a182aaa-406d-48a6-a955-ea5cb8cf5d05.png" width=400, height=300>](https://user-images.githubusercontent.com/59423092/229551011-7a182aaa-406d-48a6-a955-ea5cb8cf5d05.png)

