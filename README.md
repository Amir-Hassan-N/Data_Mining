# 🎶 Spotify Data Mining & AI-Based Music Analysis

## A Two-Phase Project on Genre Classification, Pattern Discovery, and Time-Series Analysis


This is a comprehensive two-part project focused on mining insights from the Spotify music dataset, applying both traditional data mining and advanced machine learning techniques. The projects progress from foundational classification and pattern mining (ProjectDM1) to more advanced tasks like time-series analysis, deep learning, and explainable AI (ProjectDM2).

Together, these projects explore how audio features such as tempo, energy, danceability, and others can help classify genres, identify music patterns, and predict popularity trends.

# 📁 Phase 1: ProjectDM1 – Genre Classification & Pattern Mining
## 🎯 Goals:
 ◉ Classify music genres based on audio features

 ◉ Uncover hidden patterns using clustering and association rule mining

 ◉ Predict genre labels using rule-based and statistical models

## 🛠️ Techniques Used:
Data Preprocessing: Outlier removal, normalization, transformation

Clustering: K-Means, Hierarchical, DBSCAN (Best Silhouette: 0.452)

Classification Models: Decision Tree, k-NN, Naïve Bayes

Association Rules: Apriori algorithm (Avg. Lift: 17+)

Rule-Based Classification: Achieved 96% binary accuracy (e.g., Sleep genre)

## 📌 Results:
k-NN achieved ~58.5% accuracy for genre classification

Clustering revealed genre-independent music groupings

Strong genre-affiliated rules (e.g., high acousticness = Sleep music)

# 📁 Phase 2: DM2_Report – Time-Series, Deep Learning & Explainable AI
## 🎯 Goals:
Analyze music evolution over time through time-series analysis

Apply CNN, LSTM, and MLP for genre classification

Forecast popularity and interpret models using SHAP & LIME

## 🛠️ Techniques Used:
Time-Series Analysis: PAA, Dynamic Time Warping, Shapelet Transform

Deep Learning: CNN (24.1% genre accuracy), LSTM, MLP

Advanced Classification: XGBoost, AdaBoost, Gradient Boosting

Explainable AI: SHAP & LIME to identify key predictors (e.g., danceability, popularity)

## 📌 Results:
Binary classification (Popular vs Non-Popular): 97.1% accuracy with XGBoost

Deep learning improved feature abstraction but requires larger datasets

SHAP showed interpretability in predicting genre and popularity
