# Deep-Learning-Event-Based-Trading-System
Applying deep learning (RNN, CNN) and NLP to form and test quantitative event trading system.

## Overview

This repository is based in part on preliminary work of RLQuant(https://github.com/yuriak/RLQuant)  

## News Crawlers
- Reuters news crawler
    - Based on Reuters Financial News (https://mobile.reuters.com/) 
- Social media (Twitter, etc) crawler
    - Work in progress

## Models
- [Leverage Financial News to Predict Stock Price Movements Using Word Embeddings and Deep Neural Networks](http://aclweb.org/anthology/N16-1041)  
    - A relatively standard NLP workflow
    - Bag of keywords, Polarity score, Category tag were used
    - Predict the sign of next day's return rate
- [Deep learning for event-driven stock prediction](http://dl.acm.org/citation.cfm?id=2832415.2832572)
    - OpenIE (Information Extraction) for extracting Events(subject, predicate, object)
    - Neural Tensor Network for learning Event Embedding
    - DNN, CNN can be used to predict movements
- RNN Auto-encoder for encoding news titles
    - A sequence 2 sequence AE
    - GRU was used
- [Elmo](https://arxiv.org/abs/1802.05365)
    - Using Elmo for news title encoding
    - please find tf version in [Paper_Review](https://github.com/QuantumAgent/Paper_Review)
