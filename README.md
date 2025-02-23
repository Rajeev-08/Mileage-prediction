# 🚗 Mileage Prediction - Regression Analysis  

> **A machine learning project to predict fuel efficiency (mpg) based on car attributes using the Auto MPG dataset.**  

---

## 📌 About  
This project builds a **regression model** to predict **miles per gallon (mpg)** using various car attributes like **cylinders, horsepower, weight, and displacement**. It uses **Linear Regression** from scikit-learn and evaluates model performance using **R² score and Mean Squared Error (MSE)**.

---

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Pandas & NumPy** (data handling)  
- **Matplotlib & Seaborn** (data visualization)  
- **scikit-learn** (regression model)  

---

## 📂 Dataset  
This project uses the **Auto MPG dataset** from the UCI Machine Learning Repository:  
📌 [Auto MPG Dataset](http://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data)  

**Features:**  
- `mpg` (Miles per gallon - target variable)  
- `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`  
- `model year`, `origin`, `car name`  

---

## 🚀 Installation & Usage  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/mileage-prediction.git
cd mileage-prediction
```
### 2️⃣ Install Dependencies
```sh
pip install numpy pandas matplotlib seaborn scikit-learn
```
### 3️⃣ Run the Notebook
```sh
jupyter notebook "mileage prediction.ipynb"
```
## 📊 Model Training & Evaluation
- Preprocessing:
    - Handles missing values (horsepower has missing data).
    - Uses StandardScaler to normalize numerical features.
    - pplies OneHotEncoder to categorical variables.
- Model:
    - Uses Linear Regression for predicting mpg.
    - Splits dataset into train (80%) and test (20%).

- Evaluation Metrics:
    - R² Score (Measures model performance).
    - Mean Squared Error (MSE) (Measures prediction error).
## 📸 Visualization Example
Data distribution and relationships between features:
```sh

sns.pairplot(df, diag_kind='kde')
plt.show()
```
## 🔮 Future Improvements
- Implement Polynomial Regression for better accuracy.
- Experiment with Random Forest & Gradient Boosting models.
- Deploy the model using Flask or FastAPI as a web service.
