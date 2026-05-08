# Task 2 - Sentiment Analysis with NLP

## CodTech Machine Learning Internship

### Author
Prince Winston P

---

## Project Overview

This project demonstrates sentiment analysis on customer reviews using Natural Language Processing (NLP), TF-IDF Vectorization, and Logistic Regression.

The model is trained to classify customer reviews as Positive or Negative based on review text.

---

## Technologies Used

- Python
- Scikit-learn
- Pandas
- TF-IDF Vectorization
- Logistic Regression
- Google Colab

---

## Dataset Used

Customer Reviews Dataset (`customer_reviews.tsv`)

The dataset contains:
- Positive customer reviews
- Negative customer reviews

Target Labels:
- `1` = Positive Review
- `0` = Negative Review

---

## Steps Performed

- Imported required libraries
- Loaded customer reviews dataset
- Separated features and target labels
- Applied TF-IDF Vectorization
- Split dataset into training and testing data
- Trained Logistic Regression model
- Predicted sentiments
- Calculated model accuracy
- Tested custom review prediction

---

## Analysis

The sentiment analysis model was successfully implemented using TF-IDF Vectorization and Logistic Regression.

TF-IDF converted customer review text into numerical vectors so that the machine learning model could process textual data effectively.

The Logistic Regression model learned patterns from positive and negative customer reviews and classified sentiments accordingly.

The model achieved approximately 58% accuracy on the testing dataset.

The project demonstrated the complete NLP workflow including text preprocessing, vectorization, sentiment prediction, and evaluation.

---

## Output

The model successfully predicted sentiments for customer reviews as Positive or Negative.

Example Prediction:

```text
Review: This product is very bad
Predicted Sentiment: Negative
```

---

## Conclusion

This project helped in understanding:

- Natural Language Processing (NLP)
- Sentiment Analysis
- TF-IDF Vectorization
- Logistic Regression
- Text Classification

The project successfully demonstrated how machine learning models can analyze and classify human language data.

---

## Internship Task

Completed as part of the CodTech Machine Learning Internship.