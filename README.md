# 🚗 Simple Linear Regression – Fuel Consumption vs. CO2 Emissions

## 📌 Problem Statement

The goal of this project is to explore the relationship between a vehicle’s engine characteristics and its CO2 emissions using **simple linear regression**. We aim to model how features such as engine size and fuel consumption correlate with CO2 output.

## ✅ Solution Approach

This notebook demonstrates the end-to-end implementation of **simple linear regression** using Python and scikit-learn, focusing on:

* Selecting relevant features (e.g., `ENGINESIZE`, `FUELCONSUMPTION_COMB`)
* Visualizing feature relationships with target variable (`CO2EMISSIONS`)
* Training a regression model and evaluating its performance
* Visualizing regression lines and residuals

Although the model is not tuned for high accuracy, the emphasis is on demonstrating understanding of the **modeling pipeline**, **data preprocessing**, and **visualization techniques**.

## 🛠️ Technologies & Libraries Used

* **Python 3**
* **Pandas** – for data loading and manipulation
* **NumPy** – for numerical operations
* **Matplotlib** – for plotting and visualization
* **Scikit-learn** – for implementing simple linear regression

## ▶️ How to Run

> 📍 Note: The dataset path is currently hardcoded. You may need to update the file path to run it on your local machine.

```bash
# Clone the repository (if part of one)
git clone <your-repo-url>

# Navigate to the folder and open the notebook
cd <project-folder>
jupyter notebook 01_Simple-Linear-Regression_commented.ipynb
```

## 📊 Key Results / Performance

* A basic linear regression model was trained on `ENGINESIZE` to predict `CO2EMISSIONS`.
* The result shows a **positive linear correlation**, and the regression line visually fits the data trend.
* Performance metrics like **R² score or MSE** are not explicitly computed in this notebook (🔹 can be added for further improvement).

## 📸 Visualizations

The notebook includes:

* Pairwise scatter plots between features and target
* Regression line plots
* Basic data description and correlation insights

*(sample plot: Engine Size vs. CO2 Emissions)*
📈 `ENGINESIZE ↑ → CO2EMISSIONS ↑`

## 💡 What This Project Shows About You

* You understand the **end-to-end ML workflow** for regression problems.
* You are comfortable with **exploratory data analysis (EDA)** using Python.
* You know how to work with **scikit-learn models**, even for basic prototypes.
* You document your work with **bilingual (English + Persian)** comments — a sign of clarity and communication skills.
* You showcase **learning-oriented experimentation** — even with basic or low-accuracy models — which proves awareness and curiosity.

# **Author:** mehran Asgari
## **Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com).
## **GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari).

---

## 📄 License

This project is licensed under the MIT License – see the `LICENSE` file for details.