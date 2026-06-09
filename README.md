# Women Clothing Review Analytics

## Project Overview

This project analyzes customer reviews and ratings from a women's clothing e-commerce company to understand customer behavior, identify satisfaction drivers, discover common themes in customer feedback, and build predictive models for business decision-making.

Using Exploratory Data Analysis (EDA), Natural Language Processing (NLP), Sentiment Analysis, Topic Modeling, and Machine Learning, the project transforms raw customer reviews into actionable business insights.

---

## Business Problem

A leading women's clothing e-commerce company wants to better understand its customers by analyzing demographic information, review text, ratings, and recommendation behavior.

The company aims to:

* Understand customer satisfaction patterns
* Identify positive and negative feedback trends
* Discover factors influencing product recommendations
* Analyze sentiment across customer segments
* Extract key discussion topics from reviews
* Predict customer recommendations and ratings

---

## Dataset Information

The dataset contains more than 23,000 customer reviews with the following attributes:

| Feature        | Description                             |
| -------------- | --------------------------------------- |
| Product ID     | Unique product identifier               |
| Category       | Product category                        |
| Subcategory1   | Product subcategory level 1             |
| Subcategory2   | Product subcategory level 2             |
| Location       | Customer location                       |
| Customer Age   | Age of the customer                     |
| Channel        | Purchase channel (Web/Mobile)           |
| Review Title   | Review headline                         |
| Review Text    | Detailed review                         |
| Rating         | Customer rating                         |
| Recommend Flag | Whether customer recommends the product |

---

## Project Objectives

### 1. Exploratory Data Analysis (EDA)

* Analyze customer demographics
* Understand rating distributions
* Explore recommendation behavior
* Compare product categories and subcategories
* Analyze customer behavior by location and channel

### 2. Sentiment Analysis

* Classify reviews as Positive, Negative, or Neutral
* Measure sentiment trends across categories
* Analyze sentiment by age groups, locations, and channels

### 3. Text Mining

* Identify frequently used words in reviews
* Compare positive and negative review vocabulary
* Generate word clouds

### 4. Topic Modeling

* Discover hidden themes within customer reviews
* Understand common discussion topics such as:

  * Product Fit
  * Fabric Quality
  * Delivery Experience
  * Design & Style
  * Pricing

### 5. Predictive Analytics

Build machine learning models to:

* Predict whether a customer will recommend a product
* Predict product ratings based on customer reviews

---

## Technologies Used

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn
* WordCloud

### Natural Language Processing

* NLTK
* Scikit-learn

### Machine Learning

* Logistic Regression
* Random Forest
* XGBoost

### Dashboarding

* Power BI

---

## Project Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis
4. Text Preprocessing
5. Sentiment Analysis
6. Word Frequency Analysis
7. Word Cloud Generation
8. Topic Modeling (LDA)
9. Recommendation Prediction
10. Rating Prediction
11. Dashboard Development
12. Business Insights & Recommendations

---

## Key Analyses Performed

### Customer Analysis

* Age distribution
* Recommendation trends
* Customer segmentation

### Product Analysis

* Category-wise ratings
* Subcategory performance
* Product recommendation rates

### Sentiment Analysis

* Positive vs Negative sentiment distribution
* Sentiment by category
* Sentiment by location
* Sentiment by age group
* Sentiment by channel

### Text Mining

* Most common positive keywords
* Most common negative keywords
* Review word clouds

### Topic Modeling

* Latent Dirichlet Allocation (LDA)
* Topic extraction from customer reviews

### Predictive Modeling

* Recommend Flag Classification
* Rating Prediction

---

## Dashboard Features

### Executive Overview

* Total Reviews
* Average Rating
* Recommendation Rate
* Positive Sentiment %
* Negative Sentiment %

### Customer Insights

* Age Group Analysis
* Location Analysis
* Channel Analysis

### Product Insights

* Category Performance
* Subcategory Performance
* Product Ratings

### NLP Insights

* Sentiment Analysis
* Word Clouds
* Topic Modeling Results

### Predictive Analytics

* Model Performance Metrics
* Feature Importance Analysis

---

## Repository Structure

```text
women-clothing-review-analytics/
│
├── data/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_sentiment_analysis.ipynb
│   ├── 04_topic_modeling.ipynb
│   └── 05_predictive_modeling.ipynb
│
├── dashboard/
│   └── PowerBI_Dashboard.pbix
│
├── images/
│   ├── positive_wordcloud.png
│   ├── negative_wordcloud.png
│   └── dashboard_screenshots/
│
├── requirements.txt
├── README.md
└── presentation.pptx
```

---

## Business Impact

The insights generated from this project help the business:

* Improve product offerings
* Understand customer preferences
* Enhance customer satisfaction
* Reduce negative experiences
* Optimize marketing strategies
* Increase recommendation rates
* Support data-driven decision-making

---

## Future Improvements

* Deploy sentiment analysis as a web application
* Implement real-time review monitoring
* Build advanced deep learning NLP models
* Add review summarization using Large Language Models (LLMs)
* Develop recommendation systems for customers

---

## Author

Adi

Aspiring Data Scientist | Machine Learning Enthusiast | NLP & Analytics Projects
