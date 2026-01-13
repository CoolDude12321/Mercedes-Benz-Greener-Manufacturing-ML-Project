# Mercedes-Benz-Greener-Manufacturing-ML-Project
Machine learning project to predict and reduce Mercedes-Benz test bench time by analyzing vehicle feature permutations using data preprocessing, label encoding, PCA-based dimensionality reduction, and XGBoost regression to improve testing efficiency and lower production-related emissions.

---

## 🚗 Mercedes-Benz Test Bench Time Reduction Using Machine Learning

Mercedes-Benz is a global leader in premium automobiles, known for innovation, safety, and engineering excellence. With thousands of possible feature combinations per vehicle, validating each configuration through physical testing becomes time-consuming and resource-intensive. This project applies machine learning to predict and reduce the time a vehicle spends on the test bench—improving efficiency without compromising Daimler’s high quality standards.

---

## 🎯 Project Objective

The objective of this project is to **predict the test bench time (`y`)** for a Mercedes-Benz vehicle based on its configuration features. Accurate predictions help optimize testing workflows, reduce production delays, lower operational costs, and minimize carbon dioxide emissions.

---

## 🧠 Methodology

The project follows a structured end-to-end machine learning pipeline:

### 1. Data Exploration & Cleaning
- Analyzed training and test datasets for **null values** and **unique feature counts**
- Removed **zero-variance columns** that do not contribute to prediction
- Ensured consistency between training and test datasets

### 2. Feature Encoding
- Applied **Label Encoding** to categorical features
- Safely handled **unseen categories** in the test dataset to avoid transformation errors

### 3. Dimensionality Reduction
- Implemented **Principal Component Analysis (PCA)** to reduce high-dimensional feature space
- Retained the most informative components to improve model performance and efficiency

### 4. Model Training
- Used **XGBoost Regressor**, a powerful gradient boosting algorithm for structured data
- Tuned hyperparameters such as:
  - Number of estimators
  - Learning rate
  - Tree depth
  - Subsampling ratios

### 5. Model Evaluation & Prediction
- Evaluated performance using the **R² score** on a validation dataset
- Generated predictions for unseen test data

---

## 📁 Project Structure
- Mercedes Benz Greener Manufacturing.ipynb : Python Code
- Mercedes Benz Greener Manufacturing.txt : Complete problem statement of the project
- test.csv : Test dataset
- train.csv : Train Dataset

---

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation and analysis
- **Scikit-learn** – Preprocessing, PCA, evaluation
- **XGBoost** – Regression modeling

---

## 📈 Results

The trained XGBoost model achieved a strong R² score on the validation set, demonstrating its effectiveness in predicting test bench time. This confirms the value of robust preprocessing, dimensionality reduction, and gradient boosting techniques.

---

## 🌱 Impact

This solution helps:
- Reduce vehicle testing time
- Improve manufacturing efficiency
- Lower energy consumption and CO₂ emissions
- Maintain Mercedes-Benz’s strict safety and quality standards

---

## 👤 Author
- Prakhar Srivastava
- Aspiring Data Scientist & Business Analyst | Machine Learning, Deep Learning & Generative AI Enthusiast
