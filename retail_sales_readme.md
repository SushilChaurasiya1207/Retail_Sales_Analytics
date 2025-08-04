# Retail Sales Analytics with PySpark

This project analyzes real-world retail transaction data using Apache Spark and PySpark to gain actionable business insights such as customer spending behavior, top-selling products, and regional sales trends.

## 📦 Dataset

- **Name:** Online Retail Dataset
- **Source:** UCI Machine Learning Repository
- **Format:** CSV
- **Size:** \~500K transactions
- Download Link

## 🎯 Project Objective

To simulate a real-world data engineering scenario where transactional data is cleaned, transformed, analyzed, and visualized using PySpark. This helps demonstrate scalable data processing and business intelligence capabilities.

## 🔧 Technologies Used

| Tool / Library      | Purpose                       |
| ------------------- | ----------------------------- |
| PySpark             | Distributed data processing   |
| Spark SQL           | SQL-style querying in Spark   |
| Pandas & Matplotlib | Visualization and data export |
| Jupyter Notebook    | Interactive development       |

## 📁 Project Structure

```
Retail_Sales_Analytics/
├── Online_Retails.ipynb          # Main project notebook
├── Online_Retail.csv             # Dataset file
├── sales_by_country.csv          # Final output file
├── README.md                     # Project documentation
```

## 📊 Key Features

- Load & clean dataset (remove nulls, fix date types)
- Create new columns like `TotalPrice`
- Analyze:
  - Top-selling products
  - Monthly revenue trends (UK)
  - Average order value by country
  - Customer-wise total spending
- Export final results to CSV
- Visualizations using Matplotlib

## 🔍 Sample Business Insights

- **Top Country by Revenue:** United Kingdom
- **Top 5 Products:** Paper craft items, gift bags
- **Monthly Trends:** Sales peak in Nov-Dec
- **Customer Spend:** Majority customers spent < £500

## ✅ How to Run

1. Clone the repo
2. Install dependencies: PySpark, Pandas, Matplotlib
3. Place `Online_Retail.csv` in project folder
4. Run `Online_Retails.ipynb` in Jupyter or VS Code

## 📌 Future Improvements

- Use Azure Blob to ingest data
- Automate with Azure Data Factory
- Add dashboards (Power BI or Tableau)
- Use Databricks for cloud scale

## 👨‍💻 Author

**Sushil Kumar Chaurasiya**\
Master's in Data Science | Ex .NET Developer | Aspiring Data Engineer\
[GitHub](https://github.com/SushilChaurasiya12)

---

> "This project reflects my first step into big data analytics using PySpark. I'm open to internships and projects related to Data Engineering, Azure, and Spark."

---

