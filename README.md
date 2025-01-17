# 🏠 Advanced House Price Prediction
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

> A sophisticated machine learning project to predict house prices using multiple regression algorithms and advanced data analysis techniques.

## 📊 Project Overview

This project implements a comprehensive machine learning solution for predicting house prices based on various features such as building type, zoning, construction year, and more. It leverages multiple regression algorithms to provide accurate price predictions and includes detailed data analysis and visualization.

### 🎯 Key Features

- Advanced data preprocessing and cleaning
- Extensive exploratory data analysis (EDA)
- Multiple machine learning models comparison
- Detailed visualization of categorical and numerical features
- Feature engineering and one-hot encoding
- Model performance evaluation

## 🛠️ Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Scikit-learn** - Machine learning algorithms
- **CatBoost** - Gradient boosting on decision trees

## 📋 Dataset Description

The dataset contains 13 features including:

| Feature | Description |
|---------|-------------|
| MSSubClass | Type of dwelling |
| MSZoning | Zoning classification |
| LotArea | Lot size in square feet |
| LotConfig | Lot configuration |
| BldgType | Type of building |
| OverallCond | Overall condition rating |
| YearBuilt | Original construction year |
| YearRemodAdd | Remodeling date |
| Exterior1st | Exterior covering |
| BsmtFinSF2 | Type 2 finished square feet |
| TotalBsmtSF | Total basement area |
| SalePrice | Target variable |

## 🚀 Installation and Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/house-price-prediction.git

# Navigate to the project directory
cd house-price-prediction

# Install required packages
pip install -r requirements.txt
```

## 💻 Usage

```python
# Import required libraries
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load the dataset
dataset = pd.read_excel("HousePricePrediction.xlsx")

# Run the main script
python main.py
```

## 📈 Model Performance

We implemented and compared four different regression models:

| Model | Mean Absolute Percentage Error |
|-------|-------------------------------|
| SVM | 0.18705 |
| Random Forest | 0.19294 |
| Linear Regression | 0.18741 |
| CatBoost | 0.10636 |

The Support Vector Machine (SVM) and CatBoost models showed the best performance, with CatBoost achieving the highest accuracy.

## 📊 Data Analysis Insights

### Feature Importance
- Identified key features affecting house prices
- Analyzed correlation between numerical features
- Studied distribution of categorical variables

### Visualizations
- Correlation heatmaps
- Categorical feature distribution plots
- Price distribution analysis

## 🔍 Project Structure

```
house-price-prediction/
│
├── data/
│   └── HousePricePrediction.xlsx
│
├── notebooks/
│   └── exploratory_analysis.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── utils.py
│
├── requirements.txt
├── README.md
└── main.py
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 👥 Authors

- Your Name - *Initial work* - [YourGitHub](https://github.com/stuti2305)

## 🙏 Acknowledgments

- Special thanks to contributors and data providers
- Inspiration from various real estate prediction models
- Dataset source: [Link to dataset source]

## 📧 Contact

Your Name - [@stuti](https://twitter.com/stuti) - stutimishra58@gmail.com

Project Link: [https://github.com/stuti/machine-learning](https://github.com/stuti2305/machine-learning)
