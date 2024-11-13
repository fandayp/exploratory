# Welcome to my exploratory projects!

This repository is intended as a compilation of various exploratory machine learning and data science projects I've completed to apply new techniques and technologies to real-world problems.

## Customer Review Topic Clustering

---
Notebook: [main](https://github.com/fandayp/exploratory_projects/blob/main/customer-review-topic-clustering.ipynb)

As a business owner, customer reviews can be a valuable source of insight. This project aims to segment user reviews into several topics for easier analysis.

The key components of our project include:
- **Review clustering**: to segment customer reviews into distinct clusters by representing the reviews as word vectors (combination of pre-trained [Transformer model](https://github.com/UKPLab/sentence-transformers) and self-train [Word2Vec model](https://radimrehurek.com/gensim/models/word2vec.html)),
- **Topic labeling**: to label review topics within each cluster using a large language model (LLM).

**Keywords**: review clustering, nlp, word vector, embedding, llm, word2vec, pca, autoencoder

## Timeseries prediction with AutoML

---
Notebook: [data preparation](https://github.com/fandayp/exploratory_projects/blob/main/timeseries_automl_prepare_data.ipynb), [main](https://github.com/fandayp/exploratory_projects/blob/main/timeseries_automl.ipynb)

**Forecasting**, or predicting the future value of a variable based on time series data, benefits many real-world business sectors. Its implementation can easily be found in various areas around us, such as weather prediction, stock market forecasting, and sales prediction. However, time series modeling is complex and differs from other machine learning problems, such as classification or regression.

**AutoML** stands for automatic machine learning (ML). Generally, these tools automate tasks such as model selection and hyperparameter tuning, making these processes significantly less tedious. There are drawbacks to using AutoML, such as limited flexibility in tweaking the models. However, it is an excellent tool for prototyping and validating that the dataset is not just noise.

This project is focusing on these AutoML tools for time-series forecasting:
- [AutoTS](https://winedarksea.github.io/AutoTS/build/html/source/tutorial.html), focusing on classical and traditional machine learning methods,
- [GCP AutoML](https://cloud.google.com/vertex-ai/docs/tabular-data/forecasting/overview), cloud-based solutions.

**Keywords:** time series, forecasting, automl

