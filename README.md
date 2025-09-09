

# 🏡 House Price Predictor

A machine learning project that predicts house prices using data scraped from **Zameen.com** and supplemented with the **Kaggle Zameen dataset**. The project demonstrates the end-to-end process of data collection, cleaning, preprocessing, feature engineering, and model building.

---

## 🔎 Project Overview

Real estate prices are influenced by multiple factors such as location, property size, and amenities. This project leverages data science techniques to predict property prices, providing insights into the real estate market and helping estimate house values.

---

## ⚙️ Features

* **Web Scraping**: Extracted property listings from Zameen.com using Python.
* **Data Sources**: Combined scraped data with Kaggle’s Zameen dataset.
* **Preprocessing**: Cleaned and transformed data, handled missing values, and engineered relevant features.
* **Modeling**: Implemented a **Random Forest Regressor** for price prediction.
* **Evaluation**: Used metrics like **RMSE** and **R²** to assess model performance.

---

## 🛠️ Tech Stack

* **Languages/Tools**: Python, Pandas, NumPy, Scikit-learn
* **Visualization**: Matplotlib, Seaborn
* **Model**: Random Forest Regressor

---

## 📊 Results

* Achieved accurate predictions with Random Forest compared to baseline models.
* Visualized feature importance to understand key drivers of house prices.

---

## 🚀 Future Improvements

* Add more advanced models (XGBoost, LightGBM, Neural Networks).
* Deploy the predictor as a **web app** using Flask/Django.
* Automate continuous data scraping for up-to-date predictions.

---

## 📂 Project Structure

```bash
House-Price-Predictor/
│-- data/              # Raw and cleaned datasets
│-- notebooks/         # Jupyter notebooks for EDA & modeling
│-- scripts/           # Python scripts for scraping and preprocessing
│-- models/            # Saved trained models
│-- README.md          # Project documentation
```
