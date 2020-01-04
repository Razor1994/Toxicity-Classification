# Toxicity-Classification

The project evaluates different models' ability to classify toxicity in Wikipedia Comments. The toxicity is classified into 6 lables which are not mutually exclusive. The labels are “toxic”, “severe-toxic”, “obscene”, “threat”, “insult” and “identity-hate”.

Models Evaluated:
1. Naive Bayes Model (Baseline)
2. LSTM
3. Bidirectional LSTM
4. GRU
5. Bidirectional GRU

All models were evaluated using mean-AUROC scores. Different Hyperparamters like dropouts, batch-sizes were tuned for each model. One of the key variation was the type of word-embedding used. We experimented with Glove, Word2Vec, Fast2Text and random with Xavier intialization.

Quantitative and Qualitative resulsts can be referred in the report.
