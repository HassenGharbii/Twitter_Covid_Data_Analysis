# Twitter Sentiment Analysis and Classification

This repository contains a Python script that demonstrates the process of collecting tweets related to COVID-19 vaccines, preprocessing the data, performing sentiment analysis, and classifying sentiments using different machine learning algorithms.

## Usage

### Authentication:

Replace the placeholders in the script with your Twitter API credentials.

### Finding Tweets:

Customize the `search_words` and `date_since` parameters in the script to collect relevant tweets.

### Data Preprocessing:

Tweets are cleaned, lowercased, and special characters, emojis, and short words are removed during the preprocessing steps.

### Sentiment Analysis:

Sentiment analysis is performed using the TextBlob library. Polarity and subjectivity scores are calculated for each tweet.

### Multiclass Classification:

The dataset is divided into training and validation sets.
Machine learning models like Naive Bayes, Random Forest, SVM, and Logistic Regression are used for multiclass sentiment classification.

## Code Structure

The repository is organized as follows:

- `data_collection.py`: Collects tweets using the Twitter API.
- `data_preprocessing.py`: Cleans and preprocesses the collected data.
- `sentiment_analysis.py`: Performs sentiment analysis using TextBlob.
- `classification_models.py`: Implements multiclass classification using various machine learning algorithms.
- `main_script.py`: Integrates all the above modules and provides a step-by-step execution.

## Results

The script outputs classification accuracy and performance metrics for different models.
The best-performing model for sentiment classification is identified based on the evaluation metrics.

## Conclusion

This script serves as an illustrative example of collecting, preprocessing, and analyzing tweets. It showcases how sentiment analysis and machine learning can be used for sentiment classification in real-world scenarios.

## References

- [Tweepy Documentation](http://docs.tweepy.org/en/latest/)
- [TextBlob Documentation](https://textblob.readthedocs.io/en/dev/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
