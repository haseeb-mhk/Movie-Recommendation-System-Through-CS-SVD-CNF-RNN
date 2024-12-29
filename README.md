# Movie Recommendation System

## Introduction
This project is a **Movie Recommendation System** developed using the **MovieLens 1M dataset**. The system is designed to explore and implement both basic and advanced recommendation techniques, leveraging methods ranging from similarity-based approaches to deep learning algorithms.

## Features
- Preprocessing and exploration of the MovieLens 1M dataset.
- Implementation of basic recommendation algorithms:
  - Cosine Similarity
  - Singular Value Decomposition (SVD)
- Advanced recommendation algorithms:
  - Neural Collaborative Filtering
  - Recurrent Neural Network (RNN) for sequence-based recommendations.

## Dataset
The dataset used is the **MovieLens 1M Dataset**, which includes:
- Movie details (titles, genres, etc.)
- User ratings
- Timestamps

Download the dataset from [MovieLens](https://grouplens.org/datasets/movielens/1m/).

## Project Structure
The repository contains the following files:

1. **Step 1: Data Preprocessing**
   - This file includes code for cleaning and preparing the MovieLens 1M dataset for analysis and model training.
   - Tasks:
     - Handling missing values
     - Formatting data for machine learning models

2. **Step 2: Data Exploration**
   - This file provides exploratory data analysis (EDA) to understand the dataset.
   - Insights include:
     - Distribution of user ratings
     - Popular genres
     - User and movie statistics

3. **Step 3: Basic Recommendation Algorithms**
   - Implements fundamental recommendation methods:
     - **Cosine Similarity**: Measures similarity between movies or users.
     - **Singular Value Decomposition (SVD)**: A matrix factorization technique for recommendations.

4. **Step 4: Advanced Recommendation Algorithms**
   - Focuses on deep learning-based methods:
     - **Neural Collaborative Filtering**: Combines embeddings and neural networks for improved recommendations.

5. **RNN**
   - Uses a **Recurrent Neural Network (RNN)** to capture sequential information in user interactions.
   - This method predicts future preferences based on historical sequences.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repository>.git
