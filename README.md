# Sentimental-analysis-Arabic-tweets

In this project ,Sentimental analysis is done on Arabic tweets .An Arabic-Bert-base model fromhugging face is used,it was pretrained on ~8.2 Billion words which sum up to ~95GB of text. The model achieved an accuracy of 90.16% and AUC of 0.966 on test set.

# Dataset
The data-set contains 58K Arabic tweets (47K training, 11K test) tweets annotated in positiveandnegative labels. 
The data-set is balanced and collected using positive and negative emojis lexicon. Data format: Tab-separated values TSV
Data files structure :the data folder has 4 tsv files, where negative and positive sentiments areseparated for both training and testing
Link: https://www.kaggle.com/mksaad/arabic-sentiment-twitter-corpus
