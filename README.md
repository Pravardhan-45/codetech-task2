# Sentiment Analysis for Customer Reviews

This repository contains a solution for performing sentiment analysis on a set of customer reviews. The goal is to classify each review as either **positive** or **negative** based on its content.

## Dataset

The dataset consists of 20 customer reviews along with their corresponding sentiment labels:

- `1` indicates a **positive sentiment**.
- `0` indicates a **negative sentiment**.

### Example Data:

| Review                                         | Sentiment |
|------------------------------------------------|-----------|
| Great product, very useful!                    | 1         |
| Absolutely terrible. Waste of money.           | 0         |
| I love it. Will buy again.                     | 1         |
| Not worth the price.                           | 0         |
| Fantastic service and quality.                 | 1         |
| Worst purchase I've made.                      | 0         |
| Highly recommended!                            | 1         |
| Poor quality and bad customer service.         | 0         |
| Excellent item, works perfectly.               | 1         |
| Don't buy this, it's a scam.                   | 0         |
| This is amazing, exceeded expectations!        | 1         |
| Garbage, broke after one use.                  | 0         |
| Truly wonderful experience.                    | 1         |
| Disappointed and frustrated.                   | 0         |
| Will definitely order again.                   | 1         |
| Not what I expected. Very poor.                | 0         |
| Five stars! Outstanding.                       | 1         |
| Never buying this again.                       | 0         |
| Loved it so much!                              | 1         |
| Cheap material and arrived late.               | 0         |

## Project Overview

This project applies sentiment analysis on a set of customer reviews to classify the sentiment as positive or negative. The process involves:
- Preprocessing the text data (removing stop words, stemming, etc.).
- Using machine learning techniques (e.g., Naive Bayes, SVM, or any other classifier).
- Evaluating the model’s performance using accuracy, precision, recall, etc.

The main objectives of this project are:
1. Learn how to perform text preprocessing.
2. Apply machine learning models to text data.
3. Evaluate and interpret the performance of sentiment analysis models.

## Requirements

Before running the code, ensure that the required dependencies are installed:

- **Python 3.x** or above
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - nltk (for text preprocessing)
  - matplotlib (optional, for data visualization)
  - seaborn (optional, for data visualization)

You can install the dependencies using pip:

```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn
