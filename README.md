# Movie Review Sentiment Analysis

    This repository contains a Python script that demonstrates sentiment analysis on a movie review dataset using natural language processing techniques. The dataset contains movie reviews and their corresponding sentiment labels (positive or negative).

## Dependencies

        Python 3.6 or later
        numpy
        pandas
        scikit-learn

    You can install the required dependencies using the following command:

    bash

    $ pip install numpy pandas scikit-learn

## How to use

    Clone the repository.
    Run the script sentiment_analysis.py in your Python environment.

## The script will:

    Load the dataset and display the first few rows.
    Check for missing values and remove any NaN or empty reviews.
    Display the value counts for each sentiment label (positive and negative).
    Perform exploratory data analysis on the bag of words, extracting the top 20 words per label type (excluding English stop words).
    Split the data into features (X) and labels (y), then perform a train/test split.
    Create a pipeline that creates a TF-IDF vector from the raw text data and fits a LinearSVC model.
    Train the pipeline using the training data.
    Generate a classification report and plot a confusion matrix based on the pipeline's performance on the test data.

## Example output

    The script will output a classification report and a confusion matrix to evaluate the performance of the sentiment analysis model.


    Classification Report:
              precision    recall  f1-score   support

         neg       0.81      0.87      0.84       191
         pos       0.87      0.81      0.84       209

        accuracy                           0.84       400
       macro avg       0.84      0.84      0.84       400
    weighted avg       0.84      0.84      0.84       400

    Confusion Matrix

### Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


### Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
