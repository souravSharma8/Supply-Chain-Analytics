# 📦 Supply Chain Analytics

An end-to-end **Supply Chain Analytics** project that uses **Python, Snowflake, and Power BI** to transform raw supply chain data into meaningful business insights and interactive dashboards.

---

## 📌 Project Overview

This project focuses on analyzing supply chain data for a fashion and makeup product company.

The dataset contains information related to:

* Products
* Sales
* Revenue
* Customer demographics
* Inventory and stock levels
* Suppliers
* Manufacturing
* Shipping
* Transportation
* Product quality
* Costs

The project follows an end-to-end analytics workflow:

```text
Raw Data
   ↓
Python ETL
   ↓
Data Cleaning & Transformation
   ↓
Snowflake Data Warehouse
   ↓
Power BI
   ↓
Interactive Dashboard & Business Insights
```

---

## 🎯 Objectives

The main objectives of this project are to:

* Clean and transform raw supply chain data.
* Integrate supply chain information into a structured dataset.
* Load processed data into Snowflake.
* Analyze supply chain performance.
* Identify trends and operational patterns.
* Visualize important KPIs using Power BI.
* Support data-driven supply chain decisions.

---

## 📊 Dataset

The dataset contains multiple supply chain attributes, including:

| Category       | Features                                         |
| -------------- | ------------------------------------------------ |
| Product        | Product Type, SKU, Price                         |
| Sales          | Products Sold, Revenue Generated                 |
| Customer       | Demographics                                     |
| Inventory      | Availability, Stock Levels                       |
| Orders         | Order Quantities                                 |
| Shipping       | Shipping Time, Carrier, Shipping Cost            |
| Supplier       | Supplier Name, Location                          |
| Manufacturing  | Production Volume, Lead Time, Manufacturing Cost |
| Quality        | Inspection Results, Defect Rates                 |
| Transportation | Transportation Mode, Routes                      |
| Cost           | Manufacturing, Shipping and Other Costs          |

The original project documentation describes these dataset attributes in detail.

---

# 🔄 ETL Pipeline

## 1. Extract

The raw supply chain dataset is sourced from a CSV or Excel file.

```text
Raw Supply Chain Dataset
          ↓
       Python
```

## 2. Transform

Python is used to:

* Clean the dataset.
* Handle missing values.
* Transform data into an analysis-ready format.
* Integrate relevant data into a cohesive dataset.

## 3. Load

The transformed dataset is loaded into **Snowflake** for storage and analysis.

```text
Python
   ↓
Cleaned Dataset
   ↓
Snowflake
```

This ETL workflow is described in the original project documentation.

---

# ❄️ Snowflake Data Warehouse

Snowflake is used as the centralized data warehouse for the transformed supply chain dataset.

The workflow is:

```text
Python ETL
    ↓
Processed Data
    ↓
Snowflake
    ↓
Power BI
```

This allows the processed data to be stored and queried efficiently before visualization.

---

# 📈 Power BI Dashboard

Power BI connects to the Snowflake data warehouse and provides an interactive dashboard for analyzing supply chain performance.

The dashboard can include:

* KPI cards
* Charts
* Graphs
* Tables
* Maps
* Trend analysis
* Supply chain metrics

The goal is to help users identify trends and gain insights that can support supply chain optimization.

---

# 🛠️ Technology Stack

| Technology       | Purpose                             |
| ---------------- | ----------------------------------- |
| 🐍 **Python**    | ETL and data transformation         |
| ❄️ **Snowflake** | Cloud data warehouse                |
| 📊 **Power BI**  | Data visualization and dashboarding |
| 📁 **Excel/CSV** | Source dataset                      |
| 🧮 **Pandas**    | Data processing and transformation  |

---

# 📁 Project Structure

```text
Supply-Chain-Analytics/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   └── supply_chain_data.xlsx
│   │
│   └── processed/
│       └── processed_data.csv
│
├── src/
│   ├── ETL.py
│   └── snowflake_utils.py
│
└── power_bi/
    └── supply_chain_dashboard.pbix
```

This structure follows the structure described in the original project README.

---

# 🚀 Getting Started

## Prerequisites

Install the following:

* Python
* Required Python libraries
* Snowflake account
* Power BI Desktop

---

## 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/Supply-Chain-Analytics.git
cd Supply-Chain-Analytics
```

Replace `<your-username>` with your GitHub username.

---

## 2. Install Python Dependencies

Install the required Python libraries used by the ETL scripts.

```bash
pip install pandas
```

Additional dependencies should be installed according to the project's Python scripts.

---

## 3. Run the ETL Pipeline

Run the ETL script:

```bash
python src/ETL.py
```

The ETL process extracts the raw dataset, cleans and transforms the data, and prepares it for loading into Snowflake.

---

## 4. Load Data into Snowflake

Configure your Snowflake connection and load the processed dataset into your Snowflake environment.

⚠️ **Never upload Snowflake usernames, passwords, API keys, or connection credentials to a public GitHub repository.**

Use environment variables or a local configuration file that is included in `.gitignore`.

---

## 5. Open the Power BI Dashboard

Open:

```text
power_bi/supply_chain_dashboard.pbix
```

Connect Power BI to the Snowflake data source and refresh the data.

The original project workflow specifies connecting Power BI to Snowflake and using the resulting data for dashboard creation.

---

# 📊 Analysis Areas

The project provides a foundation for analyzing:

### Sales & Revenue

* Product sales
* Revenue generation
* Product performance

### Inventory

* Stock levels
* Product availability
* Order quantities

### Suppliers

* Supplier performance
* Supplier locations
* Production volumes

### Manufacturing

* Manufacturing costs
* Manufacturing lead time
* Production volume

### Shipping & Transportation

* Shipping time
* Shipping costs
* Shipping carriers
* Transportation modes
* Routes

### Quality

* Inspection results
* Defect rates

---

# 💡 Business Insights

The Power BI dashboard is designed to help identify:

* Product and sales trends
* Inventory conditions
* Supply chain costs
* Supplier and manufacturing patterns
* Shipping performance
* Quality and defect trends
* Potential areas for operational improvement

The project aims to turn supply chain data into actionable insights for improving overall operational efficiency.

---

# 📸 Dashboard Preview




```markdown
![Supply Chain Dashboard](power_bi/dashboard_screenshot.png)
```

* Overall KPI dashboard
* Sales & revenue analysis
* Inventory analysis
* Supplier analysis
* Shipping analysis
* Manufacturing analysis

---

# 🔮 Future Enhancements

Possible future improvements include:

* Automated ETL scheduling
* Additional supply chain KPIs
* Advanced Power BI dashboards
* Predictive demand analysis
* Inventory forecasting
* Supplier performance scoring
* Automated data refresh
* Advanced cost optimization analysis

---

# 👨‍💻 Author

**Sourav Sharma**

MCA Student | Data Analytics Enthusiast

---

⭐ **If you find this project useful, feel free to explore the repository.**
