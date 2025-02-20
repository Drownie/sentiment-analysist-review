# Sentiment Analysis on Amazon Fine Food Reviews
In this project we do sentiment analysis using the amazon review as the subject. we are using NLTK vader to predict the sentiment of the review text and we also do the preprocessing on the review text.

## Project Overview

This project focuses on performing sentiment analysis on the Amazon Fine Food Review dataset. The analysis includes text preprocessing techniques such as:

- Removing unnecessary words
- Removing HTML tags
- Generating a classification report
- Computing the confusion matrix

## Results

### Confusion Matrix

```
[[  713  6486]
 [  765 42036]]
```

### Classification Report

```
              precision    recall  f1-score   support

           0       0.48      0.10      0.16      7199
           1       0.87      0.98      0.92     42801

    accuracy                           0.85     50000
   macro avg       0.67      0.54      0.54     50000
weighted avg       0.81      0.85      0.81     50000
```

## Dependencies

Ensure you have the following libraries installed before running the project:

- pandas
- nltk
- scikit-learn
- BeautifulSoup4

## How to Run

1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd <repo-name>
   ```
2. Run the jupyter code:
   ```sh
   jupyter notebook sentiment_analysis.ipynb
   ```

## License

This project is open-source and available under the MIT License.
