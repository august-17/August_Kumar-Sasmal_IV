# August_Kumar-Sasmal_IV

---

# **📌 Project 1 — Linear Regression: Stock Closing Price Prediction**

### **Overview**

This project implements a **Linear Regression model from scratch (using NumPy)** to predict the **Closing Price** of a stock using historical market data. The model is trained on features such as:

* Open Price
* High Price
* Low Price
* Momentum Index
* Beta Indicator
* Risk Premium
* Volatility Factor
* Technical Score
* Liquidity Ratio
* Trend Strength
* Quant Index
* Oscillator Value

All preprocessing (scaling, cleaning) is done manually without sklearn’s built-in models.

### **Features of the Project**

* Linear Regression built **fully from scratch**
* Gradient Descent optimization
* Custom accuracy metric
* Cost vs Epoch plot
* Train/Validation/Test split
* Predictions saved to CSV

### **How to Run**

1. Clone the repository
2. Open `linear_regression_task2_0.ipynb`
3. Run all cells
4. The model will train and generate:

   * Cost graph
   * Epoch-wise accuracy
   * Test accuracy
   * Prediction CSV file (`predictions.csv`)

### **Output**

* **Accuracy (within 10% error margin)**
* Cost curve
* Predictions for test set

---

# **📌 Project 2 — Logistic Regression: Crime Case Closure Prediction**

### **Overview**

This project uses **Logistic Regression from scratch** to classify whether a criminal case is **“Closed”** or **“Not Closed”** based on crime-related metadata.

The model is trained on columns such as:

* City
* Crime Description
* Suspect Sex
* Weapon Used
* Domain
* Area
* Age
* Police Department

Both numeric and categorical features are handled using:
✔ Manual one-hot encoding
✔ Manual feature scaling
✔ No sklearn logistic regression — everything built using NumPy

### **Features of the Project**

* Logistic Regression with Binary Cross Entropy loss
* Gradient Descent implementation
* Proper train/validation split
* No data leakage (test file used **only** for final evaluation)
* One-hot encoding + scaling implemented manually
* Final predictions saved as `crime_test_predictions.csv`

### **How to Run**

1. Clone the repository
2. Open `logistic_regression_task2_1_clean.ipynb`
3. Place `crime_train.csv` and `crime_test.csv` in the same folder
4. Run all cells
5. Final predictions will be generated

### **Output**

* Training & validation loss
* Accuracy per epoch
* Final test accuracy
* Predicted labels saved to CSV

---

# **📌 Project 3 — Ridge Regression (Bonus Task): Catch Quality Rating Prediction**

### **Overview**

This bonus project uses **Ridge Regression (L2-Regularized Linear Regression)** built from scratch to predict the **Catch Quality Rating** from previous fishing logs.

The model uses fishing-related features such as:

* Water Temperature
* Depth Pressure
* Temp-Pressure Index
* Fish Activity Metric
* Catch Density Metric

A regularization term (λ) is included, inspired by the hint:

> “a little regularisation might stop Dino from overcooking the numbers… and the fish.”

### **Features of the Project**

* Ridge Regression (L2 regularization) implemented from scratch
* Gradient Descent optimization
* Scaling + preprocessing
* Cost curve visualization
* Completely custom prediction pipeline
* Final predictions saved in `catch_quality_predictions.csv`

### **How to Run**

1. Open `ridge_regression_bonus_task.ipynb`
2. Place `fishing_logs.csv` and `prediction_logs.csv` alongside the notebook
3. Run all cells
4. The notebook will generate predicted catch quality ratings

### **Output**

* Training cost curve
* Regularized regression weights
* Predictions for unseen logs saved to CSV

---

# **📌 Skills Demonstrated**

* Linear / Logistic Regression implementation from scratch
* Gradient Descent optimization
* Feature scaling
* One-hot encoding (manual)
* Regularization (L2 / Ridge)
* Model evaluation & metrics
* Clean data preprocessing pipelines
* Train/validation/test handling without data leakage
* Jupyter Notebook ML workflows
* CSV prediction pipelines

---
