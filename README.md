# News Category Classifier
 Categorizing news topics using different ML techniqiues (extension for NewsSwipe app). A self project to learn in depth about machine learning, its pitfalls, why the architectures are designed the way they are, and how to improve them.

## Description
This project is an extension for the NewsSwipe app I built in January 2024. (checkout the app [here](https://appetize.io/app/bi3tse7tgin6xi63n46ywxikrq?device=iphone14pro&osVersion=17.2)). The main goal of this project is to categorize news articles into different categories. (e.g. sports, politics, technology, etc.) 


I'm currently using different machine learning techniques and deep learning to achieve this goal. 

Currently, I've only implemented a simple RNN model from scratch (using only pytorch), and achieving accuracy of 37% on the test set.

I'm planning to implement more complex models and techniques in the future while investigating the pitfalls of each model and documenting them.

Planned models:
- LSTM
- BERT
- GPT-2

## Dataset

The dataset used for this project is the "AG News" dataset. It is a collection of news articles from the AG's corpus of news articles on the web. The dataset contains 120,000 training samples and 7,600 testing samples from 42 different classes. 

The dataset can be found [here](https://www.kaggle.com/amananandrai/ag-news-classification-dataset), in which orignal authors implemented a ConvNet on character-level inputs. The paper can be found [here](https://papers.nips.cc/paper_files/paper/2015/file/250cf8b51c773f3f8dc8b4be867a9a02-Paper.pdf).

## Requirements
- Python 3.6+
- Pytorch
- Numpy


