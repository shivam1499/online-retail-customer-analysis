# online-retail-customer-analysis(Databricks)
This project analyzes customer purchasing behavior using transactional data from an e-commerce store. The main goal is to identify customer segments and providing insights form Data.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Databricks](https://img.shields.io/badge/Databricks-F37626?style=for-the-badge&logo=databricks&logoColor=white)

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Features & Analysis Steps](#key-features--analysis-steps)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [File Structure](#file-structure)
- [License](#license)

## Project Overview

This project explores customer transaction data from a UK-based e-commerce retailer to uncover key patterns and behaviors. Using Python within Databricks, the dataset is cleaned, processed, visualized.

## Dataset

- **Source**: [Kaggle E-Commerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- **Accessed via**: Kaggle API inside Databricks

## Key Features & Analysis Steps

1. **Data Ingestion** (via Kaggle API)
2. **Data Cleaning** (remove duplicates, nulls, negative values)
3. **Feature Engineering** (TotalPrice)
4. **Visualization of Segments & Trends**

## Technologies Used

- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- Databricks (PySpark, Notebooks)
- Kaggle API

## How to Run
1. Clone this repository to your local machine
```bash
git clone https://github.com/yourusername/ecommerce-customer-analysis-databricks.git
```
2. Open the E-Commerce Data Analysis.ipynb file in your browser or Databricks workspace.
3. Update the Kaggle API credentials (USERNAME and KEY) in the code.
4. Run the analysis and review the insights.

Then open the notebook in Jupyter or upload to Databricks.

## File Structure

```
├── data/
│   └── README.txt
├── notebooks/
│   └── ecommerce_databricks_analysis.ipynb
├── visualizations/
│   └── sales_trend.png
│   └── customer_segments.png
├── .gitignore
├── requirements.txt
├── README.md
└── LICENSE
```

## License

MIT License
