## Diabetes Prediction

A classification project using medical diagnostic data to predict the likelihood of diabetes in patients.

### Dataset
- **Source**: [Pima Indians Diabetes Dataset (Kaggle)](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Target**: `Outcome` (0 = Non-diabetic, 1 = Diabetic)
- **Features**:
  - `Pregnancies`
  - `Glucose`
  - `BloodPressure`
  - `SkinThickness`
  - `Insulin`
  - `BMI`
  - `DiabetesPedigreeFunction`
  - `Age`

### Models
- **Support Vector Classifier (SVC)**
- **Random Forest Classifier (RFC)**

### Techniques & Evaluation
- Missing value handling (replacing zeros in key features)
- Feature scaling using `StandardScaler`
- Train/Test Split with `stratify` to preserve class balance
- Model training using both SVM and RFC
- Accuracy Score:
  - ✅ SVM Accuracy: ~79%
  - ✅ Random Forest Accuracy: ~85%
- User prediction interface (custom input example)
