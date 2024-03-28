# COLLABORATIVE FILTERING RECOMMENDATION MODEL

## Overview

This project implements a collaborative filtering recommendation model utilizing cosine similarity between users' rating vectors. The model predicts movie ratings for a given user by comparing their ratings with those of similar users. It identifies movies the user hasn't watched and recommends top-rated unseen movies based on these predictions.

## Requirements

- pandas
- numpy

## Dataset

The source data for this project is obtained from Kaggle:
https://www.kaggle.com/datasets/ayushimishra2809/movielens-dataset


## Usage

1. Run the Python script `collaborative_filtering.py`.
2. The script performs the following steps:
   - Reads movie and rating data from CSV files.
   - Constructs a user-movie rating pivot table.
   - Computes cosine similarity coefficients between users.
   - Predicts movie ratings for a given user.
   - Recommends top-rated unseen movies to the user.

## Contact

For any inquiries or feedback, feel free to contact me. email: mariamsaiqodze@gmail.com



