# House-Price-Prediction-using-Linear-Regression
This project demonstrates the use of a simple linear regression model to predict numerical values based on a single or multiple input features. It is ideal for beginners to understand the fundamentals of regression modeling, evaluation metrics, and visualization.

## 📌 Project Summary

The notebook walks through the steps to:
- Load and understand the dataset
- Clean and prepare the data
- Train a linear regression model
- Visualize the regression line
- Evaluate model accuracy using standard metrics
## 📊 Technologies & Tools Used

- **Language**: Python 3.x
- **Notebook**: Jupyter
- **Libraries**:
  - `pandas` – for data handling
  - `numpy` – for numerical operations
  - `matplotlib`, `seaborn` – for data visualization
  - `scikit-learn` – for model training and evaluation

## 🧪 Steps Followed in the Notebook
1. **Importing Libraries**  
   Loaded Python packages needed for the analysis.
2. **Loading the Dataset**  
   Read the dataset using `pandas` and inspected structure, shape, and sample data.
3. **Data Cleaning**  
   - Checked for null values  
   - Renamed columns (if necessary)  
   - Converted datatypes (if needed)
4. **Exploratory Data Analysis (EDA)**  
   - Visualized relationships between features and the target variable using scatter plots and correlation heatmaps
5. **Model Building**  
   - Applied `LinearRegression()` from `sklearn.linear_model`  
   - Split the data using `train_test_split()`  
   - Trained the model on training data
6. **Model Evaluation**  
   - Evaluated predictions using:
     - **R² Score**
     - **Mean Squared Error (MSE)**
     - **Root Mean Squared Error (RMSE)**
7. **Visualization**  
   - Plotted actual vs predicted values  
   - Visualized regression line

## 📈 Example Results (Replace with your actual results)

- **R² Score**: 0.87  
- **RMSE**: 2.13
