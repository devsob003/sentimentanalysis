# Sentiment Analysis on Twitter Data

## Introduction

This project performs sentiment analysis on Twitter data related to COVID-19 vaccinations. It analyzes tweets and classifies them as positive, negative, or neutral sentiment. The data used for this analysis is sourced from Kaggle.

## Installation

To run this project, you need the following libraries installed:

- pandas
- numpy
- re
- seaborn
- matplotlib
- nltk
- textblob
- wordcloud
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib nltk textblob wordcloud scikit-learn
```
## Usage
Clone this repository to your local machine.
Download the dataset from Kaggle and save it as vaccination_tweets.csv in the project directory.
Open the Jupyter Notebook Sentiment_Analysis_Twitter_Data.ipynb.
Run the notebook cell by cell to execute the analysis.

## Dataset
The dataset used for this analysis contains Twitter data related to COVID-19 vaccinations. It includes columns like text, retweets, favorites, user location, etc. The data preprocessing steps involve removing URLs, hashtags, punctuation, and performing stemming.

## Model and Results
The sentiment analysis is performed using a logistic regression model. The accuracy achieved on the test set is approximately 84.64%. The confusion matrix and classification report provide additional insights into the model's performance.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
