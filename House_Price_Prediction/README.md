## House Price Prediction

A regression project using the California Housing dataset to predict median house values in California districts based on real-world housing features.

### Dataset
- **Source**: `fetch_california_housing()` from `scikit-learn`
- **Target**: `MedHouseVal` (Median house value in $100,000s)
- **Features**: 
  - `MedInc`: Median income in block
  - `HouseAge`: Median house age
  - `AveRooms`: Average rooms per household
  - `AveBedrms`: Average bedrooms per household
  - `Population`, `AveOccup`, `Latitude`, `Longitude`

### Model
- **XGBoost Regressor**

### Techniques & Evaluation
- Data preprocessing & visualization (Seaborn heatmap)
- Feature correlation analysis
- Train/test split (80/20)
- Model training with `XGBRegressor`
- Evaluation metrics:
  - ✅ R² Score (Train: ~0.94, Test: ~0.83)
  - ✅ Mean Absolute Error (Test: ~0.31)
- Actual vs Predicted value scatter plot
