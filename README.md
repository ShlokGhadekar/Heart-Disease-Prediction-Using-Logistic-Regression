# 🚀 Heart Disease Prediction Using Logistic Regression

## 📄 Project Overview
This project implements a **Logistic Regression model** to predict heart disease using clinical data. The model is built using **Scikit-Learn, Pandas, and NumPy** and is executed in a **Google Colab Notebook**.

## 📊 Dataset
The dataset used is `heart.csv`, which contains various medical parameters such as age, cholesterol levels, blood pressure, and more to determine the likelihood of heart disease. The dataset includes features such as age, sex, chest pain type (cp), resting blood pressure (trestbps), serum cholesterol (chol), fasting blood sugar (fbs), resting electrocardiographic results (restecg), maximum heart rate achieved (thalach), exercise induced angina (exang), ST depression induced by exercise relative to rest (oldpeak), the slope of the peak exercise ST segment (slope), number of major vessels colored by fluoroscopy (ca), and thalassemia (thal).

## 🔄 Workflow
1. Load and preprocess the dataset
2. Load and preprocess the dataset (the notebook confirms no missing values).
3. Split data into training (80%) and testing (20%) sets (using `random_state=2` for reproducibility).
4. Train a **Logistic Regression model**
5. Evaluate **accuracy** on test data
6. Predict heart disease for a sample input

## 🛠️ Installation & Usage
### Clone the Repository
```bash
git clone https://github.com/ShlokGhadekar/Heart-Disease-Prediction-Using-Logical-Regression.git
```
### Run in Google Colab
- Open `Aiminiproj.ipynb` in **Google Colab** or **Jupyter Notebook**.
- Run all the cells to train and test the model.

## ⚙️ Technologies Used
- Python 🐍  
- Pandas 📊  
- NumPy 🔢  
- Scikit-Learn 🤖  
- Google Colab ☁️  

## 📈 Model Performance
Accuracy on training data: `0.8524390243902439`
Accuracy on test data: `0.8048780487804879`

## 🎯 Example Prediction
```
Input data: (62,0,0,140,268,0,0,160,0,3.6,0,2,2)
Prediction: The person does not have a heart disease.
```

## 📚 License
This project is open-source and available under the MIT License.

