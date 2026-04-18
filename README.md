# Content-Based Movie Recommendation Engine 

## Architecture Overview
Engineered a content-based recommendation system processing a 5,000+ entry dataset.
Extracted feature matrices from raw metadata strings (genres, cast, crew).Calculated mathematical vector distances to surface highly correlated items.

## Mathematical Model
Feature Extraction: Applied Count Vectorization to map textual metadata into a discrete vector space.
Distance Metric: Implemented Cosine Similarity to measure the angular cosine distance between multi-dimensional feature vectors.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn

## Summary: 
The implemented Count Vectorization model prioritizes raw keyword frequency across metadata features, providing an immediate, lightweight computational solution that entirely bypasses the cold-start problem inherent in user-dependent collaborative filtering systems.
