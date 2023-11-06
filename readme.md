# Machine Learning for Natural Language Understanding

This was challenge task for the course work in Machine Learning for Natural Language Understanding.

## Challenge Task

Task is to train a clickbait filter to classify clickbait articles by their headline. Can freely decide how to prepare the data and which ML model to use for classification.

The challenge is considered passed if your model performs better than baseline (a simple classifier; F1 ~0.89). Report at least the F1 score of your classifier. The model will be evaluated using a hold out dataset. Prepare a script so your trained model can be evaluated with this dataset.

## Dataset

The data consists of two files, a text file with clickbait headlines and one with headlines from news sources. The hold out dataset is organized the same way.

with open('clickbait_yes') as f:
    lines = [line.rstrip() for line in f]

lines[0:10]

## Results

Submission Model performance: The Logistic regression F1 score for the given data using train:test(80:20) is 95.75 %.

The model was tested by the professor on holdout dataset and it was more than 95% accurate.
