# Bitcoin-Price-Prediction-using-Machine-Learning-in-Python

# 🚀 Bitcoin Price Prediction using Machine Learning

## 📌 Abstract

The rapid growth of cryptocurrencies, particularly Bitcoin, has attracted significant attention from investors, researchers, and financial institutions. Due to the highly volatile nature of Bitcoin, predicting its price remains a challenging task.

This project aims to develop a **Machine Learning-based predictive model** that analyzes historical Bitcoin data to forecast future price movements. By leveraging data preprocessing, feature engineering, and regression algorithms, the project provides insights into market trends and potential future values.

---

## 🎯 Objectives

* To analyze historical Bitcoin price data
* To implement Machine Learning algorithms for price prediction
* To evaluate model performance using standard metrics
* To visualize trends and patterns in cryptocurrency markets

---

## 📊 Dataset Description

The dataset used in this project contains historical Bitcoin price data, including:

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Volume

Data preprocessing steps include:

* Handling missing values
* Converting date-time formats
* Feature scaling and normalization

---

## 🔍 Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand:

* Price trends over time
* Volatility patterns
* Correlation between features

Visualizations include:

* Line plots of closing price
* Heatmaps for correlation
* Distribution plots

---

## 🧠 Machine Learning Models

The following models were implemented and compared:

### 1. Linear Regression

* Simple and interpretable model
* Used as a baseline for comparison

### 2. Decision Tree Regressor

* Captures non-linear relationships
* Prone to overfitting if not tuned

### 3. Random Forest Regressor

* Ensemble learning technique
* Improves accuracy and reduces overfitting

---

## ⚙️ Tech Stack

### Programming Language

* Python 3.x

### Libraries & Frameworks

* NumPy – numerical computations
* Pandas – data manipulation
* Matplotlib & Seaborn – data visualization
* Scikit-learn – machine learning models

---

## 📂 Project Structure

```bash
Bitcoin-Price-Prediction/
│
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for EDA & modeling
├── models/                # Saved trained models
├── src/                   # Source code files
│   ├── preprocessing.py
│   ├── train.py
│   ├── predict.py
│
├── images/                # Visualizations and plots
├── requirements.txt       # Project dependencies
└── README.md              # Documentation
```

---

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/bitcoin-price-prediction.git
```

### Step 2: Navigate to Project Directory

```bash
cd bitcoin-price-prediction
```

### Step 3: Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run Training Script

```bash
python src/train.py
```

### Run Prediction Script

```bash
python src/predict.py
```

### Using Jupyter Notebook

```bash
jupyter notebook
```

---

## 📈 Model Evaluation

The performance of models was evaluated using:

* **Mean Absolute Error (MAE)** – Measures average error
* **Mean Squared Error (MSE)** – Penalizes larger errors
* **R² Score** – Indicates goodness of fit

---

## 📉 Results & Insights

* Random Forest provided better accuracy compared to other models
* Bitcoin prices show high volatility and non-linear patterns
* Feature engineering significantly impacts prediction performance

---

## 🔮 Future Scope

* Implementation of Deep Learning models (LSTM, GRU)
* Integration with real-time cryptocurrency APIs
* Deployment using Flask or Django
* Dashboard creation for visualization
* Hyperparameter tuning for improved performance

---

## ⚠️ Limitations

* Cryptocurrency markets are highly volatile and unpredictable
* Model performance depends heavily on historical data
* External factors (news, regulations, market sentiment) are not considered

---

## 🤝 Contributing

Contributions are welcome!

If you would like to improve this project:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Gaurav Yadav**
B.Tech – Computer Science Engineering

---

## 🌟 Acknowledgements

* Open-source datasets and libraries
* Machine Learning community
* Contributors and developers

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
