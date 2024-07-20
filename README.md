# Fake News Detection using TensorFlow

Fake news detection is a crucial task in the modern digital age. This project leverages TensorFlow to build a machine learning model that can classify news articles as real or fake.

## Dataset

The dataset used for this project can be downloaded from the following link:

- https://drive.google.com/file/d/1XoHoUjZtLQ6gh_CPv9_igtZoEsdkgq3t/view?usp=sharing
- https://drive.google.com/file/d/1ekbxlI_GdF3H_XHS8U2Csj5q5AhNXhMp/view?usp=sharing

Ensure that the dataset is in the proper format before proceeding with the next steps.

## Data Cleaning

Data cleaning involves preprocessing the text data to remove noise and irrelevant information. The steps include:

1. Removing punctuation and special characters
2. Lowercasing all text
3. Removing stopwords
4. Lemmatization or stemming

Refer to the `Fake_news.ipynb` file for the implementation of these steps.

## Model Training and Testing

The dataset is split into training and testing sets to evaluate the model's performance. The steps include:

1. Splitting the data into training and testing sets
2. Vectorizing the text data using techniques like TF-IDF
3. Building the TensorFlow model
4. Training the model on the training set
5. Evaluating the model on the testing set


## Prediction

The trained model can be used to predict whether a given news article is real or fake. The prediction script takes a text input and outputs the classification result.


## Installation

To install the necessary dependencies, run:

```bash
pip install -r requirements.txt
```

Clone the repository:
```bash
git clone https://github.com/Sandhiya1335/fake-news-detection.git
cd fake-news-detection
```

Download and place the dataset in the appropriate directory.
Make predictions:
```bash
python predict.py --input "Your news article text here"
```
