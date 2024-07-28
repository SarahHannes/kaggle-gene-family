# kaggle-gene-family

### Goal
Predicting gene family from human DNA sequence

### Dataset
- Human DNA sequence with 7 gene class as target
- Dataset source: https://www.kaggle.com/datasets/neelvasani/humandnadata

### Conclusion
- Trained 3 models (MultinomialNB, XGBoost, LightGBM).
- Tried out 2 NLP processing techniques (CountVectorizer, TFIDF) -- CountVectorizer performed better than TFIDF.
- All trained model has >= 90% F1 score.
- We can predict gene class from DNA sequence with high accuracy.
