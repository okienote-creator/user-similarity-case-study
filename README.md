# Case Study 5-1 – Identifying Similar Users in a Streaming Platform

This project demonstrates how to identify similar users on a movie streaming platform using **user–user collaborative filtering**.

## Project Overview

We work with a small sample ratings dataset and walk through these main steps:
- Load the data into a pandas DataFrame
- Build a user–item ratings matrix
- Normalize user rating vectors
- Compute a user–user cosine similarity matrix
- Visualize similarities with a heatmap
- Find the top 3 users most similar to a target user

The project is designed for students learning recommender systems and similarity-based methods.

## Tools and Libraries

- Python 3
- pandas
- scikit-learn
- seaborn
- matplotlib

## Files in This Repository

- `user_similarity.ipynb` – Jupyter Notebook with all code, outputs, and visualizations
- `analysis.md` – Written interpretation of results and key concepts
- `README.md` – Project description and usage instructions

## How to Run the Notebook

1. **Clone or download** this repository.
2. Ensure you have Python 3 installed.
3. (Recommended) Create and activate a virtual environment.
4. Install dependencies:

   ```bash
   pip install pandas scikit-learn seaborn matplotlib
   ```

5. Launch Jupyter Lab or Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `user_similarity.ipynb` and run the cells in order.

## Learning Goals

By working through this notebook, you will:
- Practice building and interpreting a user–item matrix
- Learn how cosine similarity can measure user similarity
- See how similarity scores feed into collaborative filtering
- Reflect on practical limitations of user–user recommenders
