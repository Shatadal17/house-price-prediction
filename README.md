# 🏡 House Price Prediction using XGBoost Regression

Welcome to my first Machine Learning project using Python!  
This project focuses on predicting house prices using the **California Housing dataset** and the **XGBoost Regression** algorithm.

---

## 🚀 Project Overview

In this project, I implemented **Regression Analysis** using the powerful **XGBoost Regressor** to predict housing prices based on various features like population, average income, number of households, and more.

---

## 📌 Steps Performed

### 1. 📚 Importing Libraries
- pandas
- numpy
- matplotlib & seaborn (for data visualization)
- sklearn (for preprocessing, model selection, evaluation)
- xgboost (for regression modeling)

---

### 2. 🏘 Loading the Dataset
- Loaded the **California Housing dataset** using `sklearn.datasets.fetch_california_housing()`.
- Features include:

     MedInc: Median income
     HouseAge: Median house age
     AveRooms, AveBedrms, etc.
     Latitude, Longitude
     Target: Median house value for California districts (in $100,000s)
- Assigned the data to a variable `housing` and converted it into a **pandas DataFrame**.

---

### 3. 📊 Data Exploration
- Displayed sample records and described statistical summaries.
- Checked the **shape** and **info** of the dataset.

---

### 4. 🧼 Data Preprocessing
- Confirmed that the dataset contains **no missing values**.
  > If there were missing values, I would have handled them using:
  > - Dropping rows/columns
  > - Imputation techniques (mean, median, mode, etc.)
- Performed **correlation analysis** between all features.
- Used **Seaborn heatmap** to visualize the correlation.

---

### 5. ✂️ Train-Test Split
- Used `train_test_split` to divide data:
  - **80%** for training
  - **20%** for testing

---

### 6. 🤖 Model Building with XGBoost
- Used `XGBRegressor()` from the XGBoost library.
- Trained the model on training data using `.fit()`.

---

### 7. 📈 Model Evaluation
- Evaluated model performance using:
  - **R² Score** (to measure model fit)
  - **Mean Absolute Error (MAE)**
- Checked prediction accuracy on both **training and test data**.

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **XGBoost**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**

---

## 📸 Visual Examples

| 🔥 Correlation Heatmap | 📉 Predicted vs Actual |
|------------------------|------------------------|
| ![heatmap](https://github.com/user-attachments/assets/6aec0e41-e9c3-414b-83be-2a40dbe6378e) | ![Actual vs Predicted Prices](https://github.com/user-attachments/assets/f25f5a05-a33e-480b-8544-a8c7896ab203) |


---

## 💡 What I Learned
- How to load and explore a real-world dataset
- Basics of Regression Analysis
- Use of XGBoost for regression tasks
- Data preprocessing and correlation understanding
- Model evaluation using metrics like R² and MAE

---

## 💬 Feedback Welcome!

This is my **first machine learning project** and I’m excited to learn more.  
If you have any suggestions for improvements or additional analysis, 
Please feel free to comment or create a pull request! 😊

---

## 📎 References
- [California Housing Dataset (scikit-learn)](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/)
- Educational YouTube videos and articles

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/house-price-prediction-xgboost
   cd house-price-prediction-xgboost
2. Open the .ipynb notebook in Jupyter Notebook or VS Code.
3. Run the cells step by step.

   🎉 Thank you for visiting my project repo!
