# 💎 Diamond Price Prediction

A Machine Learning project that predicts the price of diamonds based on their physical and quality features such as carat, cut, color, clarity, and dimensions.

---

## 📌 Project Overview

Diamond pricing depends on multiple factors like weight, cut quality, clarity, and color. This project builds a regression model that learns from historical diamond data and predicts the price of a diamond based on its characteristics.

The goal of this project is to:

* Perform data preprocessing and feature engineering
* Train machine learning regression models
* Evaluate model performance
* Deploy or test predictions

---

## 📊 Dataset Description

The dataset contains the following features:

* **carat** – Weight of the diamond
* **cut** – Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
* **color** – Diamond color grade (D to J)
* **clarity** – Clarity grade (I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF)
* **depth** – Total depth percentage
* **table** – Width of top of diamond relative to widest point
* **x, y, z** – Dimensions (mm)
* **price** – Price in USD (Target variable)

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib / Seaborn
* (Flask if deployed)

---

## 🚀 Installation & Setup

1. Clone the repository

```bash
git clone https://github.com/abhipsa14/diamond_price_prediction.git
cd diamond_price_prediction
```

2. Create a virtual environment (recommended)

```bash
python -m venv venv
```

3. Activate the environment

Windows:

```bash
venv\Scripts\activate
```

Mac/Linux:

```bash
source venv/bin/activate
```

4. Install required dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

If using Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells.

If running as a Python script:

```bash
python main.py
```

If deployed using Flask:

```bash
python app.py
```

Then open:

```
http://127.0.0.1:5000/
```

---

## 📈 Model Evaluation

The model performance is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📌 Project Structure

```
diamond_price_prediction/
│
├── data/
├── notebooks/
├── src/
├── app.py
├── requirements.txt
└── README.md
```

---

## 🎯 Future Improvements

* Hyperparameter tuning
* Model comparison
* Deployment on cloud (AWS / Render / Railway)
* Adding CI/CD pipeline
* Creating a proper frontend UI

---
