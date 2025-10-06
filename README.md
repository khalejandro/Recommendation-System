# 📊 Yelp Restaurant Recommendation System

## 🧠 Overview

Yelp, founded in **2004**, was created to help people discover **great
local businesses**. Today, it's a massive platform combining
user-generated reviews, ratings, and metadata that empower customers to
make better decisions.

This project explores a **subset of the official Yelp dataset** to build
and compare multiple **restaurant recommendation systems**. The original
dataset is around **11GB**, but due to hardware constraints, we'll work
with a smaller, representative portion.

------------------------------------------------------------------------

## 🎯 Objective

The main goal of this case study is to design and evaluate four
different types of recommendation systems:

1.  **Knowledge/Rank-Based Recommendation System**\
    Uses explicit information like ratings and popularity to suggest top
    restaurants.

2.  **Similarity-Based Collaborative Filtering**\
    Finds users or restaurants with similar preferences and recommends
    based on shared patterns.

3.  **Matrix Factorization-Based Collaborative Filtering**\
    Employs latent features using techniques such as **SVD (Singular
    Value Decomposition)** to uncover hidden relationships between users
    and businesses.

4.  **Clustering-Based Recommendation System**\
    Groups users or restaurants into clusters based on behavioral or
    rating similarities, then recommends within those clusters.

------------------------------------------------------------------------

## 🗂️ Dataset Description

The dataset is derived from the official **Yelp Reviews Dataset** and
includes only the key attributes needed for this study:

  Attribute           Description
  ------------------- -------------------------------------
  **business_id**     Unique identifier for each business
  **business_name**   Name of the restaurant or business
  **stars**           User rating (typically from 1 to 5)
  **user_id**         Unique identifier for each user

------------------------------------------------------------------------

## ⚙️ Tools & Technologies

-   **Python**\
-   **Pandas / NumPy**\
-   **Scikit-learn**\
-   **Matplotlib / Seaborn**\
-   **Surprise / LightFM** (for collaborative filtering)

------------------------------------------------------------------------

## 📁 Repository Structure

    📦 yelp-recommendation-system
    ├── data/                   # Dataset subset used for analysis
    ├── notebooks/              # Jupyter notebooks for experiments
    ├── README.md               # Project documentation
    └── requirements.txt        # Dependencies

------------------------------------------------------------------------

## 📈 Expected Outcomes

By the end of this case study, you'll be able to:\
- Understand different recommendation techniques and their trade-offs.\
- Build, train, and evaluate various models using real-world data.\
- Visualize performance and insights that drive personalized restaurant
recommendations.

------------------------------------------------------------------------

## 📚 Acknowledgements

Dataset provided by **Yelp Open Dataset** for educational and research
purposes. [Dataset](https://drive.google.com/file/d/17wZtuKFk_gf-RLwDTcGxvKa_FIDt9CbB/view)
