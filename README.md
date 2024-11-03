
# MLFlow Projects Repository

This repository contains two machine learning projects built with MLFlow for tracking experiments and managing model versions.

- **Project**: House Price Prediction
- **DLProject**: Wine Quality Prediction using Deep Learning

## Repository Structure

- **project/**: House Price Prediction
- **dlproject/**: Wine Quality Prediction using Deep Learning

---

## House Price Prediction (Project Folder)

### Overview
This project involves predicting house prices based on various features, such as square footage, number of bedrooms, and location. The project demonstrates a full machine learning pipeline, including data preprocessing, feature engineering, model training, and evaluation.

### Features
- **Data Preprocessing**: Cleans and preprocesses the raw data.
- **Feature Engineering**: Creates new features to improve model performance.
- **Model Training**: Trains multiple machine learning models and compares them.
- **Hyperparameter Tuning**: Optimizes model parameters.
- **Model Evaluation**: Evaluates the model using metrics like Mean Squared Error (MSE) and R-squared.

### MLFlow Integration
MLFlow is used to track experiments, log parameters, and save models.

### How to Run
1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the project**:
   ```bash
   python project/main.py
   ```
3. **View MLFlow UI** (optional):
   ```bash
   mlflow ui
   ```

---

## Wine Quality Prediction (DLProject Folder)

### Overview
This deep learning project predicts the quality of wine based on its chemical properties. Using a neural network, it classifies wine quality levels from sensory and chemical attributes.

### Features
- **Data Preprocessing**: Scales and normalizes data.
- **Model Architecture**: Constructs a deep neural network using Keras.
- **Hyperparameter Tuning**: Uses Hyperopt with MLFlow to optimize learning rate and momentum.
- **Model Evaluation**: Evaluates the model using metrics like Root Mean Squared Error (RMSE).

### MLFlow Integration
- **Experiment Tracking**: Logs hyperparameters, metrics, and model versions for each run.
- **Model Registry**: Stores the trained model for future use and comparisons.

### How to Run
1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the project**:
   ```bash
   python dlproject/main.py
   ```
3. **View MLFlow UI** (optional):
   ```bash
   mlflow ui
   ```

---

## Requirements

Install the required libraries:
```bash
pip install -r requirements.txt
```

---


