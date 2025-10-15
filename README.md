# EDA-E-commerce-
Explanatory Data Analysis of e-commerce transaction data using Python and statistical visualization techniques
# E-commerce Explanatory Data Analysis Project

## Overview
This project performs comprehensive Exploratory Data Analysis (EDA) on e-commerce transaction data for RovanMart Pvt Ltd., a retail and e-commerce company operating in multiple cities across India. The analysis uncovers customer purchasing patterns, seasonal trends, and provides actionable insights for business optimization.

## Dataset
**Source**: [Ecommerce Dataset for Data Analysis](https://www.kaggle.com/datasets/shrishtimanja/ecommerce-dataset-for-data-analysis?select=project1_df.csv)
- **Size**: 55,000 transactions with 13 features
- **Time Period**: 2020-2024

### Dataset Features
- **Transaction Details**: Customer ID, Transaction ID, Purchase Date
- **Customer Demographics**: Gender, Age Group, Location
- **Product Information**: Product Category, Discount Details
- **Financial Data**: Gross Amount, Net Amount, Discount Amount
- **Payment Methods**: Credit Card, Debit Card, PhonePe UPI, Cash on Delivery

## Business Context
RovanMart Pvt Ltd. is a small retail and e-commerce company selling:
- Clothing
- Electronics
- Beauty & Health products
- Household items
- Sports & Fitness equipment
- Pet Care products

The company operates both online and offline channels across multiple Indian cities including Delhi, Mumbai, Bangalore, Chennai, Kolkata, and Ahmedabad.

## Business Questions Addressed
1. **Revenue Analysis**: Which product category generates the highest revenue?
2. **Demographics**: Which age group and gender contribute most to total sales?
3. **Regional Performance**: How do sales vary across different regions?
4. **Payment Preferences**: Which payment methods are most popular?
5. **Temporal Patterns**: How do sales fluctuate by season and time of day?
6. **Discount Impact**: What relationship exists between discount percentage and purchase frequency?

## Project Structure
```
├── README.md                                          # Project documentation
├── Explanatory_Data_Analysis_-E_Commerce.ipynb      # Main Jupyter notebook
├── explanatory_data_analysis_-e_commerce.py         # Python script version
└── data/
    └── project1_df.csv                               # Dataset (to be added)
```

## Key Analysis Components

### Data Cleaning & Preprocessing
- Handling missing values in discount fields
- Removing duplicate transactions
- Converting date formats for temporal analysis

### Feature Engineering
- **Temporal Features**: Year, Month, Day of Week, Hour
- **Time Categories**: Morning, Afternoon, Evening, Night
- **Seasonal Analysis**: Spring, Summer, Autumn, Winter
- **Discount Metrics**: Discount percentage calculations
- **Customer Behavior**: Recency analysis and churn indicators

### Analysis Highlights
- **Dataset Size**: 55,000 transactions across 4+ years
- **Product Categories**: 6 main categories analyzed
- **Geographic Coverage**: Multiple major Indian cities
- **Payment Methods**: 4 different payment options tracked
- **Temporal Granularity**: Hour-level analysis for purchasing patterns

## Technical Requirements
```python
pandas >= 1.3.0
numpy >= 1.21.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
```

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or Google Colab
- Required libraries (see requirements above)

### Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/ecommerce-eda-analysis.git
cd ecommerce-eda-analysis
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn
```

3. Download the dataset from Kaggle and place it in the `data/` folder

4. Run the analysis:
```bash
# Option 1: Jupyter Notebook
jupyter notebook Explanatory_Data_Analysis_-E_Commerce.ipynb

# Option 2: Python script
python explanatory_data_analysis_-e_commerce.py
```

## Key Findings
The analysis provides insights into:
- Peak sales periods and seasonal trends
- Customer demographic preferences
- Regional sales performance variations
- Payment method adoption patterns
- Discount strategy effectiveness
- Product category performance metrics

## Business Impact
This analysis enables RovanMart to:
- **Optimize Marketing**: Target high-value customer segments
- **Improve Inventory**: Focus on top-performing product categories
- **Enhance Strategy**: Develop region-specific approaches
- **Boost Revenue**: Optimize discount strategies for profitability
- **Data-Driven Decisions**: Establish analytics foundation for future growth

## Future Enhancements
- Customer lifetime value analysis
- Predictive modeling for sales forecasting
- Recommendation system development
- Advanced segmentation analysis
- Real-time dashboard creation

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is open source and available under the [Apache 2.0](LICENSE).

## Contact
For questions or collaboration opportunities, please reach out through GitHub issues.

---
**Note**: This project is part of a data science learning journey focused on practical business analytics and exploratory data analysis techniques.
