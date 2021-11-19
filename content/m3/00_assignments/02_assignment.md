
---
title: "M3: Mandatory Assignment"
weight: 3
disableToc: true
---

![](/SDS-2021/images/elon.jpg)

The site [https://faketrump.ai/](https://faketrump.ai/) **WAS** an interesting example of AI-powered fake-text generation. They wrote in 2019:

>We built an artificial intelligence model by fine-tuning [GPT-2](https://openai.com/blog/better-language-models/) to generate tweets in the style of Donald Trump’s Twitter account. After seeing the results, we also built a discriminator that can accurately detect fake tweets 77% of the time — think you can beat our classifier? Try it yourself!

Unfortunately, they decided to take down the site and the dataset. Also Tump is gone...
Therefore: Elon it is!

GPT-2 is a neural transformer-based model, that has been announced by OpenAI in February 2019 and created considerable discussion because they decided - in contrast to their earlier policies - not to release the mode to the public. Their central argument was that the model could be used to produce fake news, spam and alike too easily. The footnote of the faketrump page reads: “Generating realistic fake text has become much more accessible. We hope to highlight the current state of text generation to demonstrate how difficult it is to discern fiction from reality.”


Since then several organizations and researchers have shown that it is [possible to develop systems to detect “fake text”](https://www.theguardian.com/technology/2019/jul/04/ai-fake-text-gpt-2-concerns-false-information). We believe that you too can implement a competitive system.

Having no dataset from that projects, Roman decided to retrain GPT-2 to generate new fake Elon tweets. If they can do that, we can do that! However, it seems as if it is easier for ML models to identify our fake tweets...well...they are an AI company and probably spent more time on that...


This assignment is not about Natural Language Processing (NLP) but about being able to deal with sequential data using deep learning. Some basic knowledge from M2 can be useful to squeeze the last 1% performance but you should be able to get great results with pure Keras. The data can be found [here](https://github.com/SDS-AAU/SDS-master/raw/master/M3/assignments/find_elon.gz) and has the following format:


<table>
  <tr>
   <td>0
   </td>
   <td>1
   </td>
  </tr>
  <tr>
   <td>string
   </td>
   <td>boolean
   </td>
  </tr>
</table>

There are 1577 real Elon tweets and 1577 fake ones.

Having been with us for M2, you may ask: How do I go from text to numerical values that I can use in a neural model?
You can for instance just use the “Tokenizer” that’s part of Keras. 


```vocabulary_size = 5000
tokenizer = Tokenizer(num_words= vocabulary_size)
tokenizer.fit_on_texts(df['text'])
sequences = tokenizer.texts_to_sequences(df['text'])
```
This will turn the tweets into sequences of indices. From here, you just need to “pad” the sequences (for en easier workflow).
Each tweet can then look like that:

```
array([   0,    0,    0,    0,    0,    0,    0,    0,    0,    0,    0,
          0,    0,    0,    0,    0,    0,    0,    0,    0,    0,    0,
          0,    0,    0,    0,    0,    0,    0,    0,    0,    0,    0,
          0,    0,    0,    0,    0,    0,    0,    0,    0,    0,    0,
          0,    0,    0,    0,    0,    0,   47,  160,  981,  332,    6,
        122,    8,    1,  324,   46, 1375, 3242,  122,  421,   61,   57,
         30,  134,    1, 4266,   24,    6,  149,  669,  623,   11,  272,
        738,   86, 1999,  308,    1,   89,  938,    1,   50,   49, 1683,
         83,   32,   18,    6,    5, 1168, 1939,   30,  871,   58,    1,
        612], dtype=int32)
```
Here, the tweets were padded to a length of 100 with pre-padding (leading 0s are attached to reach the same length for all tweets).

But what kind of network do you expect me to build?

That’s up to you. Just make sure it is more advanced than a basic feed-forward-net.

Not acceptable solution: You use SpaCy or similar to get average vectors (or TFIDF weighed avg Vecs.) for the tweets and then build an M1 style classifier just using a neural model rather than a random forest or similar.

If you want to build such a simple model as a baseline - that’s fine, but we do expect that you come up with something more advanced.


*   You can use CNNs, RNNs (GRU, LSTM, BiLSTMS), Embedding layers in combinations that you think are useful (explain your choices). 
*   If you want, you are welcome to use pre-trained word-vectors (public domain or homemade). 
*   You can go even deeper and explore transformer-based models, attention and the more recent 2018-21 stuff. Have a look at [SpaCy-Transformers](https://spacy.io/universe/project/spacy-transformers) and [Simpletransformers](https://simpletransformers.ai/)
*   BUT: A top-performance can be achieved just using Keras and no fancy Transformer stuff. Be creative and use the 100s of tutorials and recipes on the web.

![alt_text](https://pbs.twimg.com/media/EI7DWlmXsAAwCte?format=jpg&name=4096x4096)



### Deliverables

Please submit a PDF or HTML version of your notebook on peergrade.io (if you submit HTML, please zip it before - large embedded HTMLs from causing crashing when opened directly in peergrade). Please make sure it runs without errors and others can access it (i.e. own test in “anonymous” setting in your browser).

<!-- Deadline is Monday, 22.11, 23:59. -->

This notebook should:

*   solve the questions in a straightforward and elegant way.
*   contain enough explanations to enable your fellow students (or others on a similar level of knowledge) to clearly understand what you are doing, why, what is the outcome, how to interpret it, and how to reconstruct the exercise. Be specific and understandable, but brief.



<!-- 
## Solutions


* R team [:::: HERE ::::](https://sds-aau.github.io/SDS-master/M2/exercises/xxx)
* Py team [:::: HERE ::::](https://colab.research.google.com/github/SDS-AAU/SDS-master/blob/master/M2/notebooks/xxx) -->
     





 
