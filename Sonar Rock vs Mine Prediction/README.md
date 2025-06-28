## 🌊 Sonar Rock vs Mine Prediction

A binary classification project using the Sonar dataset to predict whether sonar signals reflect off a metal cylinder (mine) or a rock based on 60 frequency energy features.

### 📊 Dataset
- **Dataset:** [Dataset](./dataset.csv)
- **Target:** Rock (R) or Mine (M)
- **Features:**
  - 60 numeric attributes (Energy within a frequency band)
  - No missing values; fully numeric

### 🧠 Models
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

### 🧪 Techniques & Evaluation
- Data standardization with `StandardScaler`
- Stratified train/test split (80/20)
- Model training with each algorithm
- Evaluation metrics:
  - ✅ Accuracy Score
  - ✅ Confusion Matrix Heatmap
  - ✅ Classification Report
  - ✅ ROC Curve & AUC Score
- Random Forest feature importance visualization

### 📎 Notebooks
- `Prediction_with_LogisticRegression.ipynb`
- `Prediction_with_SVM.ipynb`
- `Prediction_with_RandomForest.ipynb`
