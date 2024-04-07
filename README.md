
# Instagram Reach Analysis using Python

## Overview

This repository contains a Python script to analyze Instagram reach based on various factors such as impressions, likes, comments, shares, profile visits, and follows. The script reads the "Instagram.csv" dataset, performs exploratory data analysis, visualizes the data using different plots, and builds a machine learning model to predict Instagram impressions.



## About the Project

The main objective of this project is to analyze and understand Instagram reach based on various metrics such as impressions, likes, comments, shares, profile visits, and follows. The script provides insights into the performance of Instagram posts and helps in predicting the impressions using a machine learning model.

## Dataset

The dataset used in this project is "Instagram.csv", which contains information about Instagram posts, including impressions, likes, comments, shares, profile visits, and follows.

## Getting Started

### Prerequisites

Before running the script, ensure you have the following installed:

- Python (3.x recommended)
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- wordcloud
- scikit-learn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/instagram-reach-analysis.git
cd instagram-reach-analysis
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Analysis

### Instagram Reach

The script analyzes the distribution of impressions from various sources such as home, hashtags, and explore using seaborn and plotly.

### Content Analysis

Word clouds are generated to visualize the most frequent words in captions and hashtags using the WordCloud library.

### Relationship Analysis

Scatter plots with trendlines are used to analyze the relationship between likes, comments, shares, saves, and profile visits with impressions.

### Conversion Rate

The conversion rate is calculated based on the total number of follows divided by profile visits.

## Instagram Reach Prediction Model

A PassiveAggressiveRegressor model is trained using the likes, saves, comments, shares, profile visits, and follows as features to predict the impressions. The model's accuracy is evaluated using the R^2 score on the test dataset.

##images
![image](https://github.com/AISHWARYAAU/Instagram-Reach-Analysis-using-python/assets/91381783/b0a2d7ea-4f80-42d7-b856-8e41f4539d81)
![image](https://github.com/AISHWARYAAU/Instagram-Reach-Analysis-using-python/assets/91381783/86983222-22ab-4963-b2e6-5753fd9fd403)
![image](https://github.com/AISHWARYAAU/Instagram-Reach-Analysis-using-python/assets/91381783/a2506ef0-f62b-4974-85a2-934e1236eb22)



