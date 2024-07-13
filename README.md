# California Housing Price Predictor 
--- 
![California Housing Prices](images/housing_price.jpg)

## Project Overview
This project aims to build a machine learning model to predict California housing prices using data from the 1990 California census. Although the dataset is historical and may not reflect current housing prices like more contemporary datasets (e.g., Zillow Zestimate), it serves as an excellent introduction to the basics of machine learning and data analysis.

--- 


## Dataset
The dataset used in this project contains information from the 1990 California census. It includes various features such as the number of rooms, number of bedrooms, population, household information, and geographical location, along with the median house value which is the target variable.

---

## Installation

Clone the repository:
``` bash
git clone https://github.com/yourusername/California-Housing-Price-Predictor.git
cd California-Housing-Price-Predictor
```

---

## Usage
1. Open the Jupyter notebook:
``` bash
jupyter notebook notebooks/california_housing_price_predictor.ipynb
```
2.	Follow the steps in the notebook to understand the data analysis, preprocessing, feature engineering, model training, and evaluation.

---
## Exploratory Data Analysis (EDA)
-	Visualize the data distribution and relationships between features.
-	Plot histograms, scatter plots, and correlation matrices to gain insights into the data.

---
## Data Preprocessing

-	Apply log transformations to normalize skewed distributions.
-	Encode categorical variables using one-hot encoding.
-	Scale the features using StandardScaler.

---
## Feature Engineering

-	Create new features such as bedroom_ratio (total bedrooms / total rooms) and household_rooms (total rooms / households) to provide additional information to the model.

---
## Model Training and Evaluation

1.	Linear Regression:
    - Train a Linear Regression model on the scaled training data.
    - Evaluate the model’s performance on the test data.
2.	Random Forest Regressor:
    - Train a Random Forest Regressor on the scaled training data.
    - Evaluate the model’s performance on the test data.

---
## Results
- The Linear Regression model provided a baseline performance.
- The Random Forest Regressor showed improved accuracy by capturing non-linear relationships and interactions between features.

---
## Future Work
- **Hyperparameter Tuning**: Optimize model performance by tuning parameters.
- **Additional Features**: Include more relevant features like proximity to amenities.
- **Advanced Models**: Experiment with Gradient Boosting, XGBoost, or deep learning.
- **Cross-Validation**: Ensure robustness and generalizability with cross-validation.
- **Current Data**: Use recent datasets for more relevant predictions.

---
## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

---
