# Simple Movie Recommender System

This repository contains code for a simple movie recommender system built using the Python library Surprise. The project demonstrates how to implement and evaluate recommender systems using different algorithms on the MovieLens 100K dataset.

## Installation

To run the project, you need Python installed on your system. Then, you'll need to install the Surprise library. You can install it using pip:

```bash
pip install scikit-surprise
```

## Dataset

The project uses the `MovieLens 100K` dataset which is directly loaded using Surprise's built-in dataset loader.

## Structure

The project includes:

- Loading the dataset.
- Splitting the data into training and testing sets.
- Implementing a K-Nearest Neighbors (KNN) recommender.
- Implementing a Singular Value Decomposition (SVD) recommender.
- Evaluating both models using Root Mean Square Error (RMSE).
- Generating recommendations for a specific user.

## Usage

To run the recommender system, simply execute the Python script:

```bash
python recommender_system.py
```

This will train the KNN and SVD models on the MovieLens data, evaluate them, and make some sample predictions.

## Code Overview

- **Data Loading**: The MovieLens 100K dataset is loaded.
- **Train-Test Split**: The dataset is split into training and testing data.
- **Training the Recommender Systems**:
  - A KNN-based recommender is trained.
  - An SVD-based recommender is trained.
- **Evaluating the Systems**: The performance of both recommenders is evaluated using RMSE.
- **Making Recommendations**: Recommendations are made for a user who has already rated some movies.

## Contributing

Contributions to the project are welcome. Please ensure to update tests as appropriate.

## License

Distributed under the MIT License. See `LICENSE` for more information.
```
