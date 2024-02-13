# Zomato Restaurant Data Analysis and Cost Prediction

## EDA Part - Exploring Restaurant Data for Insights and Patterns

**Objectives:**
- Analyze a dataset of restaurant information to uncover hidden patterns and trends.
- Identify key factors influencing restaurant popularity, rating, and customer engagement.

**Data Exploration and Analysis:**
- Explored the distribution of features such as rating, cost, number of reviews, and number of followers.
- Visualized data using various plots to identify relationships between features.
- Calculated correlation coefficients to quantify the strength and direction of relationships.

**Clustering:**
- Applied K-Means clustering to segment restaurants into distinct groups based on multiple features.
- Evaluated clustering results using silhouette score and Davies-Bouldin Index.
- Visualized clusters using t-SNE to understand their distribution and characteristics.

**Key Findings:**
- Identified six distinct clusters of restaurants based on features.
- Discovered weak negative correlation between cost and rating.
- Found positive correlation between the number of reviews and followers.

**Conclusions:**
- Provided insights into factors influencing restaurant popularity.
- Clusters can inform tailored marketing strategies and service improvements.

## Clustering Analysis and Sentiment Analysis

**Objectives:**
- Identify clusters of restaurants based on characteristics and reviews.
- Investigate the relationship between sentiment and factors such as cost, cuisine, and review length.
- Develop a model to predict sentiment scores for new reviews.

**Key Steps:**
- Cleaned and preprocessed review text data.
- Applied KMeans clustering to group restaurants.
- Utilized VADER sentiment analysis for sentiment scores.
- Trained regression models for sentiment prediction.

**Conclusions:**
- Revealed four distinct restaurant clusters.
- Analyzed sentiment distribution and factors affecting sentiment.
- Random Forest Regression model demonstrated high accuracy in predicting sentiment scores.

## Model Building Part - Predicting Restaurant Cost

**Objectives:**
- Predict the cost of a restaurant based on various features.
- Train and evaluate machine learning regression models.

**Key Steps:**
- Preprocessed data by handling missing values and encoding categorical variables.
- Trained models including Random Forest Regressor, Linear Regression, Decision Tree Regressor, and Gradient Boosting Regressor.
- Performed hyperparameter tuning using GridSearchCV and RandomizedSearchCV.

**Best Model:**
- Gradient Boosting Regressor with optimized hyperparameters.
- Achieved R^2 score of 0.9636, MSE of 937.4970, RMSE of 30.6186, and MAE of 12.2596.

**Conclusions:**
- Successfully applied machine learning to predict restaurant costs.
- The best model achieved high accuracy and generalizability.

This project provides comprehensive insights into restaurant data, sentiment analysis, and cost prediction, empowering businesses to make informed decisions.

