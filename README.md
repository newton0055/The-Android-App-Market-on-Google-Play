# Android App Market Analysis

This project aims to conduct a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. The objective is to gain insights from the data and devise strategies to drive growth and retention in the highly competitive app market.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Data Analysis](#data-analysis)
- [App Insights](#app-insights)
- [User Reviews](#user-reviews)
- [Sentiment Analysis](#sentiment-analysis)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Mobile apps have become ubiquitous and offer significant opportunities for both creators and businesses to thrive. The ease of app development and potential for profitability have led to a surge in app development. This project aims to analyze the Android app market and provide insights that can help drive growth and retention strategies for app developers.

## Dataset
The dataset used in this project consists of two files:

1. apps.csv: This file contains details of apps available on Google Play. It includes features such as App Name, Category, Rating, Reviews, Size, Installs, Type (Paid or Free), Price, and Last Updated.

2. user_reviews.csv: This file contains a random sample of 100 most helpful first user reviews for each app. The reviews have been pre-processed and include features such as App Name, Review Text, Sentiment Category (Positive, Negative, or Neutral), Sentiment Score (ranging from -1 to 1), and Sentiment Subjectivity.

## Installation
To run the project, follow these steps:

1. Clone the repository:
```
git clone https://github.com/your-username/android-app-market-analysis.git
cd android-app-market-analysis
```
2. Create a virtual environment (optional):
```
python3 -m venv venv
source venv/bin/activate
```
3. Install the required packages:
```
pip install -r requirements.txt
```

## Data Analysis
The project begins with exploratory data analysis to understand the characteristics of the Android app market dataset. This step involves examining the distribution of app categories, ratings, reviews, sizes, and other relevant features. Visualizations and statistical summaries are used to gain insights.

## App Insights
Based on the data analysis, the project provides key insights into the Android app market. These insights may include popular app categories, highest-rated apps, most downloaded apps, pricing trends, and recent update patterns. The findings can help developers understand market trends and make informed decisions regarding app development and marketing strategies.

## User Reviews
User reviews play a crucial role in app success and user engagement. The project analyzes user reviews to uncover patterns and sentiments expressed by users. This analysis can identify common user sentiments, highlight positive or negative aspects of apps, and provide feedback for developers to improve their apps and enhance user satisfaction.

## Sentiment Analysis
Sentiment analysis is performed on user reviews to gauge the overall sentiment of users towards specific apps. By using sentiment scores and subjectivity measures, the project aims to understand the general sentiment distribution and identify apps with highly positive or negative reviews. This information can guide developers in focusing on areas that need improvement or leveraging positive feedback for marketing purposes.

## Usage
Once the project is set up and the data is analyzed, the insights and findings can be utilized by app developers, marketers, and stakeholders in the Android app market. The information can inform decision-making regarding app development, category selection, pricing strategies, user engagement, and user satisfaction enhancement.

## Contributing
Contributions to the project are welcome. If you have any suggestions, bug reports, or feature

 requests, please open an issue on the project's GitHub repository.

## License
The project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the code for both commercial and non-commercial purposes.
