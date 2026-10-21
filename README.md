# 🏠 Boston House Price Prediction App

A Streamlit web app that estimates a house price from user-provided property features using a trained machine-learning model.

## ✨ Overview

The app loads a saved model and feature-column configuration, collects numeric inputs, and displays a predicted price. The project also explores regression workflows such as feature engineering, data cleaning, outlier detection, scaling, and regularized regression.

## 🧰 Tech Stack

- Python
- Streamlit
- pandas and NumPy
- scikit-learn model artifacts (serialized with pickle)

## 🚀 Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/pushkarsingh88603-data/Boston_House_Price_Prediction_App.git
   cd Boston_House_Price_Prediction_App
   ```
2. Create and activate a virtual environment (recommended).
3. Install the app dependencies:
   ```bash
   pip install streamlit pandas numpy scikit-learn
   ```
4. Confirm the required saved model and feature files (including `model.pkl` and `columns.pkl`) are present in the project directory.
5. Start the app:
   ```bash
   streamlit run app.py
   ```

## 🖥️ How It Works

1. Loads the trained model and expected input columns.
2. Presents numeric fields for the model features.
3. Builds a one-row DataFrame from the entered values.
4. Displays the model's estimated house price.

## 📁 Main Files

- `app.py` — Streamlit prediction interface.
- `APP.ipynb` — notebook associated with the project.
- `House_Price_Prediction_Model.ipynb` — model-development notebook.

## ⚠️ Notes

- Predictions depend on the training data, preprocessing, and feature definitions used when the model was created.
- Only use trusted model files with pickle; loading untrusted pickle files can execute unsafe code.
- This is an educational estimation tool, not a formal property valuation.

## 👤 Author

**Pushkar Singh** · [GitHub profile](https://github.com/pushkarsingh88603-data)
