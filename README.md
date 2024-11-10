
## Sentiment Analysis of Social Media Posts

**Project Overview**

This project involves analyzing a large dataset of around 30,000 social media posts to predict the sentiment of a given statement. Using the Multinomial Naive Bayes algorithm, the project demonstrates a simple Natural Language Processing (NLP) workflow, including data cleaning and vectorization to ensure accurate sentiment predictions.

**Project Objectives**
- Data Extraction and Preparation: Extract, clean, and prepare social media posts for NLP processing.
- Sentiment Prediction: Use a Multinomial Naive Bayes classifier to predict sentiment (positive, negative, or neutral).
- NLP Interpretation: Showcase fundamental NLP techniques like text vectorization for sentiment analysis.

**Features**
- Large Dataset of Social Media Posts: An extensive dataset with 30,000 posts covering diverse topics and sentiments.
- Multinomial Naive Bayes Model: Predicts the sentiment of each post, providing a simple and interpretable NLP solution.
- Data Cleaning: Removal of irrelevant information and noise to improve model accuracy.
- Vectorization: Use of techniques like TF-IDF or Count Vectorization to transform text into a format suitable for model training.

**Requirements**
- Python 3.x
- Libraries:
  - Pandas: For data handling
  - Scikit-Learn: For the Naive Bayes model and vectorization
  - NLTK or SpaCy: For text preprocessing
  - NumPy: For numerical operations

Install the required libraries with:

```bash
pip install pandas scikit-learn nltk numpy
```

**Usage**
- Clone the repository.
- Run the preprocessing script to clean and vectorize the data.
- Execute the model script to train the Naive Bayes model and predict sentiment on new statements.

**Key Components**
- Data Cleaning: Tokenization, removal of stop words, and other preprocessing steps.
- Text Vectorization: Transforming text data into numerical features.
- Sentiment Classification: Predicting the sentiment label for each post.

**Insights**

This project provides a foundation for sentiment analysis using basic NLP methods, suitable for applications in social media monitoring, customer feedback analysis, and opinion mining.

**License**

This project is licensed under the MIT License.
