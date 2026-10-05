This Natural Language Processing project analyzes tweets published during the COVID-19 pandemic and classifies their sentiment into five categories: Extremely Negative, Negative, Neutral, Positive, and Extremely Positive.
The project uses the COVID-19 NLP Text Classification dataset, containing more than 40,000 labelled tweets for training and a separate test set.


Methodology


- Exploratory analysis of the dataset and sentiment distribution.
- Removal of URLs, mentions, hashtags, numbers, and non-alphabetic characters.
- Lowercasing, tokenization, stop-word removal, and lemmatization with NLTK.
- Conversion of cleaned tweets into TF-IDF features.
- Multiclass sentiment classification using multinomial logistic regression.
- Evaluation through classification metrics and a confusion matrix.
