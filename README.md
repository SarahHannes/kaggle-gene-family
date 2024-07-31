# kaggle-gene-family
<a target="_blank" href="https://colab.research.google.com/github/SarahHannes/kaggle-gene-family/blob/main/predicting-gene-family-from-dna-sequence.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

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
