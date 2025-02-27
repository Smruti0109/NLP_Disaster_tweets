# NLP_Disaster_tweets
Twitter has become an important communication channel in times of emergency.
Smartphones enable people to announce an emergency they’re observing in real-time. Because of this, agencies like disaster relief organizations and news agencies are increasingly interested in programmatically monitoring Twitter.

However, it’s not always clear whether a person’s words actually announce a disaster. For example:

A tweet using the word "ABLAZE" may be metaphorical rather than indicating a real fire. While this is clear to humans, it's challenging for machines to interpret accurately.

## Objective
This competition challenges you to build a machine learning model that predicts whether tweets describe real disasters. The dataset contains 10,000 hand-classified tweets.

## Approach
- **Text Preprocessing**: Cleaning text by removing URLs, hashtags, mentions, punctuation, and numbers.
- **Feature Extraction**: Using `TfidfVectorizer` with n-grams.
- **Model Training**: Applying `Logistic Regression` for classification.
- **Evaluation**: Using F1-score for performance measurement.
- **Prediction**: Generating predictions on test data.
- **Submission**: Creating `submission.csv` for Kaggle.

## Clone the repository
```bash
git clone https://github.com/Smruti0109/NLP_Disaster_tweets.git
```
## Results
The model achieves a high F1-score, ensuring effective classification of disaster-related tweets.
