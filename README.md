Financial News Article Classification: GitHub Repository
Overview:

This repository contains the implementation of a text classification model designed to predict whether a company's stock (specifically APPL) goes up or down based on financial news articles. The project follows a structured approach from initial data exploration to modeling using machine learning algorithms.
Repository Structure:

The core of this project resides within the notebook folder. Here's a brief overview of each notebook:

    exploration_notebook.ipynb:
        This is the starting point of our analysis.
        Initial exploration of the dataset to gain insights into the data distribution.
        Highlights include finding common words, indicative words, and a dispersion plot.

    descriptive_statistics.ipynb:
        Detailed descriptive statistics of the dataset.
        Provides insights into the distribution, variance, and characteristics of the data.

    creating_prediction_dataset.ipynb:
        This notebook handles the merging of US news articles with APPL stock prices.
        The outcome of this process is a labeled dataset, where each article is associated with either a '0' (stock goes down) or '1' (stock goes up).

    preprocess_dataset.ipynb:
        Contains preprocessing steps applied to the dataset.
        The focus is on data cleaning, normalization, and preparing the data for modeling.

    word_2_vec.ipynb:
        This notebook creates the Word2Vec model.
        Here we transform articles into vector representations that can be fed into the machine learning models.

    naivebayes_rndomforest_classifiers.ipynb:
        The prediction part of our modeling process.
        Implementation and evaluation of two classifiers: Gaussian Naive Bayes and Random Forest.
        Provides insights into hyperparameter tuning, model evaluation, and results.

If you're reviewing this project, the notebooks are structured in a logical flow. Start with the exploration, moving through preprocessing, and ending with the modeling for a comprehensive understanding.
