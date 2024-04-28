## Project Overview

**Challenge:** In a competitive market, the success of restaurants can often be unpredictable. Understanding what drives restaurant success or failure from online reviews can provide actionable insights.

**Goal:** This project uses Yelp reviews to identify key factors that influence the success of restaurants in California before the COVID-19 pandemic, leveraging BERT model predictions to provide strategic insights for restaurant owners.

## Dataset

The dataset consists of nearly 7 million Yelp reviews, focusing on the attributes of restaurants and their customer reviews to determine what influences restaurant success.

## Data Preparation

**Text Pre-processing:** Involved sentiment analysis, tokenization, and cleaning steps to prepare text data for modeling.

**BERT Model Preparation:** The initial application of the BERT model created embeddings from the pre-processed text, which were used to predict the operational status ('is_open') of the restaurants based on reviews and star ratings.

## Modeling and Evaluation

### Models Implemented:
- **Initial BERT Model Prediction:** Used to forecast the likelihood of a restaurant being operational.
- **BERT Model Post Parameter Tuning:** Adjustments made to the BERT parameters after initial results to improve prediction accuracy.

### Performance Metrics:
Comparison of model performances pre and post-tuning based on precision, recall, and F1-score.

### Winning Approach:
**Optimized BERT Model:** Showed improved prediction accuracy with a fine-tuned approach, enhancing the model's ability to distinguish between open and closed restaurants.

## Business Impact

### Topic Analysis:
Identified five distinct topics from the reviews that are frequently associated with either positive or negative outcomes for restaurants.

### Strategic Insights:
The insights from the BERT model provide a nuanced understanding of how customer feedback in reviews translates to real-world restaurant performance.

## Deployment Strategies

- **Model Deployment:** Recommendations on how to deploy the model in a real-world environment to assist restaurant owners in making informed decisions.
- **Continuous Improvement:** Suggests the ongoing refinement of model parameters and strategies based on new data and feedback.
