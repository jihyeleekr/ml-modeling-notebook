## Fake_News_Detection

A binary text classification project using a news dataset to predict whether a news article is real or fake based on its text content.

### Dataset
- **Dataset:** News articles labeled as FAKE or REAL
- **Target:** FAKE (0) or REAL (1)
- **Features:**
  - Raw text/title of news articles
  - Preprocessed with lowercasing, punctuation removal, stopword removal, regex cleaning

### Models
- Logistic Regression (LR)
- Gradient Boosting Classifier (GBC)
- Decision Tree Classifier (DT)
- Random Forest Classifier (RFC)

### Techniques & Evaluation
- Text vectorization using CountVectorizer and/or TF-IDF Vectorizer
- Stratified train/test split (e.g., 80/20)
- Model training and comparison with each algorithm
- Evaluation metrics:
  - ✅ Accuracy Score
  - ✅ Confusion Matrix Grid (side-by-side for all models)
  - ✅ Classification Report

### Notebooks
- `Fake_News_Detection.ipynb`
