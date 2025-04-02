# h&m-fashion-recommendation
H&M Personalized Fashion Recommendation System (Kaggle Project)

# Personalized Fashion Recommendation for E-Commerce

This project builds and evaluates multiple recommendation system approaches using H&M’s fashion retail dataset from Kaggle. The goal is to improve product suggestions for customers by testing models such as collaborative filtering, content-based filtering, RFM segmentation, and ALS matrix factorization. Performance is evaluated using MAP@12.

**Dataset Link:** [H&M Kaggle Competition](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data)

---

## Project Overview

H&M customers often face overwhelming product choices. This project uses 30M+ transaction records, product metadata, and customer profiles to build models that recommend relevant fashion items. Our team implemented and compared six different recommendation approaches to identify which performs best for fashion e-commerce.

---

## Tools & Technologies
- Python (NumPy, pandas, scikit-learn)
- Recommendation algorithms (Content-Based, ALS, KNN, Clustering)
- Evaluation metric: MAP@12
- Kaggle Notebook

---

## Methodology

- Downsampled to 6-week transaction window to reflect fast fashion cycle
- Built & compared 6 models:
  - Content-Based Filtering (TF-IDF + Cosine Similarity & KNN)
  - User-Based Collaborative Filtering (Gower Distance)
  - RFM + KMeans Clustering + Association Rule Mining
  - Alternating Least Squares (ALS) Matrix Factorization
  - Item-Based Collaborative Filtering

---

## Key Findings

- ALS models drive personalized recommendations that boost customer engagements
- Quality of features matters more than quantity: additional features may introduce noise rather than value
- Multiple recommendation approaches enable versatile business solutions: addressing cold-start problems, personalizing existing user experiences, and efficiently promoting new products

---

## Future Work

- Work further on user-based collaborative filtering algorithms to resolve cold start issue
- Hybrid recommender systems
- Apply more advanced machine-learning algorithms like Recurrent Neural Networks(RNN),Multilayer Perceptron (MLP)
- Integrate visual features from image data using CNN to capture preferences and combine them with textual features

---

## Files

- `notebooks/`: Contains my part of notebook with EDA, Content-Based Filtering modeling, and evaluation
- `data/`: (Not uploaded) Dataset available on Kaggle at [this link](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data)
- `images/`: Visualizations like MAP@12 chart or similarity heatmaps used in this README
- `Project_Report.pdf`: Final group report including background, methods, results, and conclusions

