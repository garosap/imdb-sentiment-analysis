
# Sentiment Analysis on IMDB Movie Reviews

## Overview

This project was developed as part of an introductory lab lecture to ML at Athens University of Economics and Business.

It is focused on performing sentiment analysis on a dataset of 50,000 movie reviews from IMDB. The goal is to accurately predict whether a given review has a positive or negative sentiment using machine learning techniques. This repository contains a Jupyter notebook that outlines the process from data collection to model evaluation and iteration.

## Contents

- `README.md`: This file, providing an overview of the project and instructions on how to set up and run the notebook.
- `Sentiment_Analysis_IMDB_Reviews.ipynb`: The Jupyter notebook containing the complete workflow for the sentiment analysis project, including data preprocessing, model training, evaluation, and iteration strategies for improving model performance.
- `dataset/`: Directory containing the IMDB Dataset. Please download the dataset from [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) and place it here. The dataset should be named `IMDB_Dataset.csv`.

## Getting Started

### Prerequisites

To run this notebook, you'll need the following:
- Python 3.6 or later
- Jupyter Notebook or JupyterLab
- The following Python packages: `pandas`, `sklearn`, `nltk`

### Installation

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/garosap/imdb-sentiment-analysis.git
   ```
2. Install the required Python packages using:
   ```
   pip install pandas scikit-learn nltk
   ```
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) and place it in the `dataset/` directory.

### Running the Notebook

You can either run the notebook using VScode (suggested for simplicity) or Jupyter Notebook/Lab. To run the notebook using Jupyter Notebook/Lab, follow these steps:

1. Navigate to the cloned repository's directory.
2. Start Jupyter Notebook or JupyterLab:
   ```
   jupyter notebook
   ```
   or
   ```
   jupyter lab
   ```
3. Open the `Sentiment_Analysis_IMDB_Reviews.ipynb` notebook.
4. Run the cells in order to execute the sentiment analysis workflow.

