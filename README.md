# Disaster

Classifying if tweets are about real disasters

## Structure

Since this is about classifying if text from tweets (Natural Language) are about real disaster. We need to turn the text into vectors.

To do this we are using TF-IDF, term frequencfy-inverse document frequency. This gets the frequency of all words across the tweets and allows us to turn them into vectors.

For the classifying, we are going to figure something out.
- [ ] SVM
- [ ] Logistic Regression
- [ ] SGD
- [ ] Nearest Neighbors
- [ ] Decision Trees

The classification is represented with `0` and `1`
- `1` = real disaster
- `0` = not disaster

## Setup

### Install packages

To install all the required python libraries run

```
pip install -r requirement.txt
```

while in the root of the directory

### Download data

To download the data testing and training datasets go to [this link.](https://www.kaggle.com/competitions/nlp-getting-started)


# Links
[kaggle](https://www.kaggle.com/competitions/nlp-getting-started)