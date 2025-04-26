# 📊 Retail Sales Prediction Project

## 📌 Objective
Predict product sales across stores in Ecuador using machine learning, based on historical data, promotions, holidays, and oil prices.

## 🛠️ Technologies
- **Python 3**
- **Key Libraries**:
  - pandas, numpy
  - scikit-learn
  - matplotlib, seaborn

## 📂 Data Structure
Dataset contains:
- **Train/Test**: 3M+ records
- **Supplementary Data**:
  - Store metadata (city, state, cluster)
  - Oil prices
  - Holiday calendars
  - Store transactions

## 🔧 Feature Engineering
Key engineered features:
- Temporal components (year, month, day)
- Cyclical date features (sine/cosine transforms)
- Holiday indicators
- Oil price interpolation
- Transaction data
- Store clusters

## 🧠 Implemented Model - Decision Tree Regressor
### Model Performance
- **RMSLE**: 0.691 (Root Mean Squared Logarithmic Error)
- **MAE**: 9.76 (Mean Absolute Error)

### Feature Importance
| Feature               | Importance |
|-----------------------|------------|
| Product Family        | 42.4%      |
| Transactions          | 22.9%      |
| Promotion Status      | 20.9%      |
| Store Number          | 2.7%       |
| Store Cluster         | 2.1%       |
