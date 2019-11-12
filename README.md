![](https://i.imgur.com/lzJdggI.png)
![](https://i.imgur.com/4PxqDeW.png)

# Applying Deep Transfer Learning for Natural Language Processing (NLP)

Handling tough real-world problems in Natural Language Processing (NLP) include tackling with class imbalance and the lack of availability of enough labeled data for training. Thanks to the recent advancements in deep transfer learning in NLP, we have been able to make rapid strides in not only tackling these problems but also leverage these models for diverse downstream NLP tasks.

The intent of this hack session is two-fold, we will first look at various SOTA models in deep transfer learning for NLP with hands-on examples and then talk about how these models were used in a real-world industry use-case around proactive detection of security vulnerabilities.

## Part 1 - Deep Transfer Learning Techniques for NLP

In this first part of this hands-on hack session, we will take a trip through the various advances in deep transfer learning for NLP including the following:

- Pre-trained word embeddings for Deep Learning Models (FastText with CNNs\Bi-directional LSTMs + Attention)
- Universal Embeddings (Sentence Encoders, NNLMs)
- Transformers (BERT, DistilBERT)

We will take a benchmark classification dataset and train and compare the performance of these models. All examples will be showcased using Python and leveraging the latest and best of TensorFlow 2.0.

## Part 2 - Industry Case Study: Proactive Identification of Software Dependency Vulnerabilities

The second part of this hack session will briefly cover a real-world industry use case around proactive detection of security vulnerabilities in software. The idea here is that open-source and third-party libraries (dependencies) can often cost any enterprise dearly since they are not often aware of potential vulnerabilities which might be present in these dependencies. Can we leverage deep learning to proactively find out and flag dependencies having a sign of a potential vulnerability before it becomes a serious issue (Example: the requests library from python was one of the most vulnerable dependencies in the recent past which a lot of developers were not even aware of!).

This solution uses state-of-the-art deep learning models in NLP like BERT to go through public data including GitHub events data, Bugzilla, Mailing list conversations to predict probable security vulnerabilities. This should give the audience an idea of how we leveraged deep transfer learning for NLP in a very unique domain and also tackle problems like extreme class imbalance.


## Key Takeaways from this Hack Session
- Learn to train and fine-tune pre-trained SOTA models including BERT and DistilBERT for downstream NLP tasks like classification
- Examples showcased using the latest and best in TensorFlow 2.0, TF-Hub and the excellent Transformers framework
- Learn about a real-world industry use-case on predicting software dependency vulnerabilities using these techniques
