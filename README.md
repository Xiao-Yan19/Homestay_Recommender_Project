# Homestay Recommendation System for West and North Sikkim

## Project Overview
This project develops a recommendation system for homestays in West and North Sikkim using machine learning techniques.

The system analyses user preferences, homestay features and previous ratings to recommend suitable homestays.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Recommendation Techniques
1. Content-Based Filtering
2. Item-Based Collaborative Filtering
3. Item-Average Baseline
4. Matrix Factorisation using Stochastic Gradient Descent (Bonus)

## Dataset
The project uses three datasets:
- items.csv
- users.csv
- ratings.csv

**Note:** The dataset is synthetic and is intended for academic demonstration.

## Model Evaluation

| Model | RMSE |
|---|---:|
| Content-Based Filtering | 0.898732 |
| Item-Based Collaborative Filtering | 0.999392 |
| Matrix Factorisation (λ = 0.1) | 1.012430 |
| Matrix Factorisation (λ = 0.01) | 1.092026 |
| Item-Average Baseline | 1.184991 |

Content-Based Filtering achieved the lowest RMSE in our evaluation.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all cells from beginning to end.

## Project Submission
This repository contains the complete implementation and the two-page project summary.