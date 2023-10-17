---

# Lead Scoring Analysis for X Education

## Overview
In the evolving landscape of digital education, X Education stands out as a prominent e-learning platform. While the platform currently experiences a lead-to-customer conversion rate of 30%, there is a significant opportunity to optimize this metric. This project undertakes the challenge of systematically prioritizing leads, ensuring that sales resources are directed effectively.

## Table of Contents
1. Introduction
2. Data Description
3. Exploratory Data Analysis (EDA)
4. Model Building
5. Evaluation Metrics
6. Key Takeaways
7. Business Strategies
8. Conclusions

## Introduction
This analysis aims to devise a logistic regression model that assigns a lead score, ranging between 0 and 100, to each prospective customer. This score signifies the probability of lead conversion, enabling X Education to fine-tune its resource allocation strategies.

## Data Description
The dataset comprises various features such as:
- Customer activity metrics (e.g., `TotalVisits`, `AvgPageViews`)
- Geographic information (`City`, `Country`)
- Engagement tags (`Tags`)
- Source of lead (`Origin`, `Referral`, `Source`)
... and many more.

The target variable, `Converted`, indicates successful lead conversion.

## Exploratory Data Analysis (EDA)
Initial data exploration revealed:
- An imbalanced conversion rate distribution
- Potential outliers in specific features
- Significant categorical features influencing lead conversions

## Model Building
A logistic regression model was employed, given its adeptness at predicting probabilities. The model was trained using a subset of the data.

## Evaluation Metrics
The model's performance on the test set demonstrated:
- An accuracy of approximately 91.23%
- Strong precision and recall metrics

## Key Takeaways
Certain tags, specifically "Lost to EINS", "Closed by Horizzon", and "Will revert after reading the email", emerged as highly influential in determining conversion likelihood.

## Business Strategies
Recommendations for various business scenarios were provided, including strategies for aggressive conversion phases and suggestions for minimizing outreach during quieter business periods.

## Conclusions
The logistic regression model serves as a robust foundation for enhancing X Education's lead conversion strategy. With further refinement and the integration of more complex algorithms, there's potential to achieve even greater accuracy.


