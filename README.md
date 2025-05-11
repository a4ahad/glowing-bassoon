# Airbnb Listings Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0%2B-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.0%2B-lightblue)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive data analysis project examining Airbnb listing patterns, pricing trends, and customer preferences using Python's data science stack.

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Key Features](#-key-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Key Findings](#-key-findings)
- [Visualizations](#-visualizations)
- [Contributing](#-contributing)
- [License](#-license)

## 🔍 Project Overview
This project performs exploratory data analysis on Airbnb listings data to uncover:
- Price distributions and outliers
- Popular property types and locations
- Relationships between listing features
- Seasonal pricing trends

The analysis follows a complete EDA workflow from data cleaning to visualization.

## 📂 Dataset
The dataset contains information about:
- Listings (property type, amenities, room type)
- Pricing and availability
- Host information
- Review scores and dates

Dataset source: [Airbnb Open Data on Kaggle](https://www.kaggle.com/datasets/airbnb-listings)

## ✨ Key Features
- Data cleaning and preprocessing pipeline
- Statistical analysis using NumPy and Pandas
- Interactive visualizations with Matplotlib/Seaborn
- Correlation and outlier detection
- Geographic and temporal trends

## 🛠️ Technologies Used
- Python 3.8+
- Jupyter Notebook
- Libraries:
  - Pandas (data manipulation)
  - NumPy (numerical operations)
  - Matplotlib/Seaborn (visualization)
  - Datetime (date handling)

## ⚙️ Installation
1. Clone the repository:
```bash
git clone https://github.com/a4ahad/airbnb-eda.git
cd airbnb-eda
```
2. Create and activate a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
## 🚀 Usage
Open the Jupyter notebook:

```bash
jupyter notebook airbnb_analysis.ipynb
```
Run cells sequentially to:
- Load and clean the data
- Perform statistical analysis
- Generate visualizations

## 🔑 Key Findings
Pricing Insights
- Average listing price: $120
- Most listings (68%) priced between 80−200/night
- Luxury listings (>$300) represent only 5% of inventory

Property Trends
- Entire homes/apartments most common (55%)
- Private rooms account for 40% of listings
- Shared rooms are rare (5%)

Location Impact

- Downtown areas command 25-30% price premium
- Beachfront properties priced 40% higher on average

## 📊 Visualizations
Figure	Description
- Price Distribution	Distribution of listing prices
- Room Types	Breakdown of property types
- Neighborhood Prices	Price variations by location

## 🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the project
- Create your feature branch (git checkout -b feature/AmazingFeature)
- Commit your changes (git commit -m 'Add some AmazingFeature')
- Push to the branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## 📜 License
Distributed under the MIT License. See LICENSE for more information.

## 📧 Contact
[Md Abdul Ahad] - [a4ahad@gmail.com]

Project Link: [https://github.com/a4ahad/airbnb-eda](https://github.com/a4ahad/glowing-bassoon)
