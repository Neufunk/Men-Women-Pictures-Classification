![Python version](https://img.shields.io/badge/Python-3.6%7C3.7-blue.svg)
![FastAI version](https://img.shields.io/badge/fastai-1.0.51-blue.svg)
![PyTorch version](https://img.shields.io/badge/pytorch-1.0.1-blue.svg)
![Dataset](https://img.shields.io/badge/Dataset-Original-lightgrey.svg)
![download](https://img.shields.io/github/downloads/neufunk/Men-Women-Pictures-Classification/total.svg)

# Description

A Convolutional Neural Network trained to classify pictures of men/women.

Following the fast.ai course on Neural Networks, I didn't want to simply reproduce the notebooks with the same results, so I tried to apply my knowledges to another problem.

Classifying men/women tend to be more tedious, because humans can be either very similar, or very different, in a physical way.

# Dataset

I've created this dataset on my own, collecting images from Google Images.
It's manually collected and cleansed dataset containing **3.354 pictures** (jpg) of men (1414 files) and women (1940 files).
There should be close to none mislabeled files left.

Download the cleansed dataset from Kaggle @ https://www.kaggle.com/playlist/men-women-classification

You can also download the raw dataset from Google, following the instructions in the notebook


# Frameworks
- fastai 1.0.51
- pandas
- numpy
- pytorch 1.0.1 **OR** pytorch-cpu 1.0.1