## Overview

During the period December 2017 - March 2018, Kaggle held a competition called [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview). The goal was to identify and classify online toxic comments at Wikipedia. A full description of this competition can be found on the Kaggle site.

Two of the solutions in this repo use NLP. The first solution uses text vectorization with classic machine learning - an ensemble of gradient boosting, random forests, and logistic regression. The second solution uses word embeddings with deep learning (an LSTM). 

The other two solutions in this repo use text statistics. The first solution uses classic machine learning - an ensemble of gradient boosting, random forests, logistic regression, and a support vector machine. The second solution uses deep learning (an MLP). 

## Description of Competition (from Kaggle site)

Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.

The Conversation AI team, a research initiative founded by Jigsaw and Google (both a part of Alphabet) are working on tools to help improve online conversation. One area of focus is the study of negative online behaviors, like toxic comments (i.e. comments that are rude, disrespectful or otherwise likely to make someone leave a discussion). So far they’ve built a range of publicly available models served through the Perspective API, including toxicity. But the current models still make errors, and they don’t allow users to select which types of toxicity they’re interested in finding (e.g. some platforms may be fine with profanity, but not with other types of toxic content).

In this competition, you’re challenged to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and respectful.
