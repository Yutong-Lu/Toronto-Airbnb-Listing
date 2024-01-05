# Model of Toronto Airbnb Listing Prices: Impact of Instant Bookability

**Author:** Yutong Lu
**Date:** December 19, 2021

## Abstract

- Study aims to determine if the 'instantly bookable' feature affects Airbnb listing prices in Toronto.
- Data from Inside Airbnb, scraped on November 6th or 7th, 2021.
- Analysis includes features of the host, accommodation, and reviews.
- Propensity score matching and multiple linear regression models used for analysis.
- Result: Instant bookability is not significantly related to listing prices.

## Keywords

- Sharing Economy, Airbnb, Pricing, Causal Inference, Propensity Score Matching.

## Introduction

- Focus on Airbnb, a major platform in the sharing economy.
- Study whether certain features, like instant bookability, affect listing prices.
- Research hypothesizes that instantly bookable listings have lower prices.

## Data

### Data Collection Process

- Data from Inside Airbnb, reflecting listings during early November 2021.
- Contains features like room type, beds, price, reviews, and instant bookability.

### Data Cleaning and Summary

- Cleaned data to focus on essential variables.
- Final dataset: 11023 observations, 16 variables.
- Variables: room type, beds, price, minimum nights, reviews, instant bookability, etc.

## Methods

### Propensity Score Matching

- Used to control confounding variables and mimic randomized experiments.
- Treatment group: Instantly bookable listings.

### Multiple Linear Regression

- Model built to analyze relationship between listing prices and features including instant bookability.

## Results

- Logistic regression used to predict propensity scores for matching.
- Final linear regression model included 9 predictors, with instant bookability not showing significant impact on prices.

## Conclusions

- Instant bookability does not causally relate to listing prices.
- Other factors like room type, number of beds, and reviews play a significant role in pricing.
- Suggests focusing on these aspects for better understanding of Airbnb pricing in Toronto.
