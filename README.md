# 📊 Burger King Pricing Analysis 

### Internship Project | SQL + Python + Power BI

This project was completed during my internship to analyze Burger King’s menu pricing data and generate data-driven business insights.

The goal was to evaluate pricing consistency, identify high-value products, detect pricing risks, and support strategic pricing decisions using a full analytics pipeline.

---

## 🎯 Problem Statement

To analyze menu pricing data across stores and quarters in order to:

- Evaluate pricing consistency
- Identify high-value products
- Detect overpriced and risk-prone items
- Understand pricing power across menu categories
- Support data-driven pricing optimization

---

## 🛠 Tech Stack

- **MySQL** – Data extraction
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
- **Jupyter Notebook** – Analysis workflow
- **Power BI** – Interactive dashboard visualization

---

## 🔄 Project Workflow

### 1️⃣ Data Extraction
- Pulled structured menu data from a MySQL database
- Queried store-level and product-level attributes
- Imported data into Python for processing

### 2️⃣ Data Cleaning & Preprocessing
- Removed irrelevant categories
- Handled empty strings and missing values
- Converted data types (dates, numeric fields)
- Removed duplicate entries
- Filtered zero-calorie and non-relevant items

### 3️⃣ Feature Engineering
- Created value-based metrics (e.g., calories per price)
- Built segmentation logic for product evaluation
- Generated derived fields to support pricing analysis

### 4️⃣ Exploratory Data Analysis
- Analyzed pricing distribution
- Compared quarter-wise trends
- Evaluated category-level pricing performance
- Identified value outliers

### 5️⃣ Product Segmentation
Products were categorized into:

- High-Value Products
- Overpriced Products
- Pricing Power Products
- Reputation-Risk Items
- Safe Products

Segmentation was based on value metrics, pricing patterns, and business logic.

### 6️⃣ Data Visualization
- Built analytical charts using Matplotlib
- Highlighted pricing patterns and distribution
- Visualized category and product-level insights

### 7️⃣ BI Dashboard
- Developed an interactive Power BI dashboard
- Summarized insights for business decision-making
- Enabled quick evaluation of pricing health and performance

---

## 📈 Key Insights

- Identified products delivering maximum value per price
- Flagged potentially overpriced or low-value items
- Detected pricing power in specific menu categories
- Observed quarter-over-quarter pricing patterns
- Highlighted segments requiring pricing review

---

## 📂 Repository Structure

## 📂 Repository Structure

```
burger-king-pricing-analysis/
│
├── 01_data_cleaning.ipynb      # Data extraction & preprocessing
├── 02_pricing_analysis.ipynb   # EDA & business insights
├── burger_king_dashboard.pdf   # Power BI dashboard export
├── requirements.txt            # Project dependencies
├── .gitignore                  # Ignored system & secret files
└── README.md                   # Project documentation
```

## 🔐 Data Access

The dataset used in this project is stored in a MySQL database.

To run this project locally:

1. Create a MySQL database.
2. Import the required tables.
3. Configure your database credentials using a `.env` file.
4. Execute the notebooks to perform data extraction and analysis.

Database credentials are not included for security reasons.

## 🚀 Project Highlights

- End-to-end analytics workflow (Database → Python → Dashboard)
- Real-world internship business case
- Combination of SQL, data cleaning, segmentation, and visualization
- Focus on business impact, not just technical implementation

---

## 👨‍💻 Author

Shivam  
Aspiring Data Analyst | SQL | Python | Business Intelligence
