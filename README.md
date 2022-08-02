This is a fake news detector, using Transformer (Distilbert).

I am using data from news_articles.csv to train Distilbert then scaling it to another Fake vs Real News dataset that is larger.

Currently the F1 score after training on news_articles.csv is ~83% which is better than the fake news detector in the main branch of this repo.

The model seems to be overfitting on fake news since the training loss gets lower but the validation loss gets higher.

There will be more improvements to come.