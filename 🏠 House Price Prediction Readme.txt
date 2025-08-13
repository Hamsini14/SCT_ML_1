🏠 House Price Prediction using Linear Regression

This project predicts house prices based on various features such as square footage, number of bedrooms, bathrooms.  
It uses Python, Pandas, Scikit-learn, and Matplotlib/Seaborn for analysis, modeling, and visualization.

📌 Process
- Data preprocessing and cleaning (handling missing values, creating derived features).
- Feature engineering (`TotalArea` from multiple area-related features).
- Linear Regression model for price prediction.
- Model evaluation using:
  - R² Score
  - Mean Squared Error (MSE)
- Visualizations for:
  - Price distribution
  - Correlation heatmap
  - Scatter plots
- User input feature for predicting prices interactively.

📂 Dataset
The dataset contains the following relevant features:
- `GrLivArea` - Above ground living area in square feet.
- `TotalBsmtSF` - Total basement area in square feet.
- `LotArea` - Lot size in square feet.
- `BedroomAbvGr` - Number of bedrooms above ground.
- `FullBath` - Number of full bathrooms.
- `SalePrice` - Target variable (price of the house).
