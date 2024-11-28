# SMS Spam Classification

## Overview
This project focuses on classifying SMS messages as **spam** or **ham** using machine learning techniques. The model helps identify unsolicited and potentially harmful messages efficiently.

## Dataset Used
- **Source**: [SMS Spam Collection v.1](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)  
- **Description**: Contains 5,574 SMS messages labeled as `ham` (legitimate) or `spam`.
- **Key Features**:
  - `label`: Indicates whether the message is `ham` or `spam`.
  - `message`: The content of the SMS.

## Technologies Used
- **Libraries**: `pandas`, `scikit-learn`, `gensim`, `NLTK`.
- **Techniques**:
  - Text Preprocessing: Tokenization, lowercasing, stopword removal.
  - Vectorization: `CountVectorizer`, `TF-IDF Vectorizer`, Word2Vec (`gensim`).

## Model
- **Algorithm**: Multinomial Naive Bayes.
- **Evaluation**:
  - Performance was measured using accuracy, precision, recall, and F1-score.


