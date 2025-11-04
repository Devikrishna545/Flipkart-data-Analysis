# 🛒 Flipkart Discount Analysis & Product Sales Prediction

A data science project analyzing Flipkart fashion products to predict the most selling items during major discount events like Big Billion Days.

## 📋 Project Overview

In the competitive world of e-commerce sales and marketing, predicting which products will be bestsellers during discount events is crucial. This project analyzes Flipkart's fashion product dataset to identify:
- Brands offering the highest discounts
- Product categories with maximum discounts
- Patterns in pricing strategies
- Most selling products during promotional events

The insights from this analysis help in understanding consumer behavior during discount periods (50-100% off) and building predictive models for sales forecasting.

## 🎯 Objective

**Primary Goal:** Develop a machine learning model that predicts the most selling products during discount days

**Secondary Goals:**
- Analyze discount patterns across different brands
- Identify top-performing product categories
- Understand pricing strategies during promotional events
- Extract actionable insights for sales forecasting

## 📊 Data Description

### Dataset Source
- **Platform:** Kaggle
- **URL:** [Flipkart Fashion Products Dataset](https://www.kaggle.com/datasets/aaditshukla/flipkart-fasion-products-dataset)
- **Format:** JSON (converted to CSV)
- **Size:** 30,000 records
- **Features:** 18 columns

### Key Features
The dataset includes various attributes such as:
- Product information (name, brand, category)
- Pricing details (original price, discounted price)
- Discount percentages
- Product ratings and reviews
- Product specifications
- And more...

## 🔄 Project Workflow

### 1. Data Collection
- Source: Kaggle dataset in JSON format
- Conversion: JSON → CSV for easier processing
- Initial exploration of data structure

### 2. Data Preprocessing & Cleaning
- **Handling Missing Values**
  - Identifying null/missing entries
  - Imputation strategies for different features
  - Removing irrelevant records

- **Data Type Conversion**
  - Converting string prices to numeric
  - Standardizing date formats
  - Categorical encoding

- **Feature Engineering**
  - Calculating discount percentages
  - Creating price categories
  - Extracting brand and category insights
  - Creating derived features

- **Data Validation**
  - Removing duplicates
  - Handling outliers
  - Ensuring data consistency

### 3. Exploratory Data Analysis (EDA)
- Statistical summary of features
- Distribution analysis of prices and discounts
- Brand-wise discount patterns
- Category-wise sales trends
- Correlation analysis

### 4. Feature Selection
- Identifying relevant features for prediction
- Feature importance analysis
- Dimensionality reduction if needed

### 5. Model Development
- Algorithm selection
- Training and validation split
- Model training
- Hyperparameter tuning

### 6. Model Evaluation
- Performance metrics
- Validation results
- Model comparison

## 📁 Repository Structure

```

```

## 🚀 Getting Started

### Prerequisites
```bash
Python >= 3.8
pandas >= 1.3.0
numpy >= 1.21.0
scikit-learn >= 0.24.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
jupyter >= 1.0.0
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Devikrishna545/flipkart-discount-analysis.git
cd flipkart-discount-analysis
```

2. **Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Download the dataset**
- Visit the [Kaggle dataset page](https://www.kaggle.com/datasets/aaditshukla/flipkart-fasion-products-dataset)
- Download and place in `data/raw/` directory

### Running the Analysis

```bash
# Launch Jupyter Notebook
jupyter notebook

# Navigate to notebooks/ and run them in sequence
```

## 📈 Key Insights

*(This section will be updated with findings)*

- Top brands offering maximum discounts
- Product categories with highest sales during discount days
- Price range analysis
- Discount patterns and trends

## 🔮 Model Performance

*(Will be updated after model development)*

- Model accuracy
- Precision and recall
- Feature importance
- Prediction results

## 🛠️ Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Scikit-learn** - Machine learning models
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development

## 📝 Future Enhancements

- [ ] Real-time price tracking integration
- [ ] Sentiment analysis from product reviews
- [ ] Time-series forecasting for seasonal trends
- [ ] Web scraping for live data updates
- [ ] Deployment as a web application
- [ ] Integration with recommendation systems

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Kaggle for providing the dataset
- Aadit Shukla for the original dataset compilation
- Flipkart for the data source

## 📧 Contact

**Devikrishna545**
- GitHub: [@Devikrishna545](https://github.com/Devikrishna545)
- Project Link: [https://github.com/Devikrishna545/flipkart-discount-analysis](https://github.com/Devikrishna545/flipkart-discount-analysis)

## 📊 Project Status

🔄 **In Progress** - Currently in Data Preprocessing & Cleaning phase

---

⭐ **If you find this project useful, please consider giving it a star!**

*Last Updated: November 4, 2025*
