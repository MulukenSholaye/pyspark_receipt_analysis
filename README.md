# PySpark Invoice Analysis
This project is a comprehensive PySpark notebook (invoice_analysis.ipynb) designed to perform in-depth data analysis on a financial invoice dataset. It leverages PySpark for scalable data processing and uses matplotlib and seaborn for data visualization. The notebook provides key business insights into financial health, vendor performance, and sales trends.
![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/285061c246ab26062909d7b82b946c6754a42bf9/einvoice-online-digital-statements-concept-260nw-2488413193.webp)
# Key Features
The notebook is structured to walk you through a complete data analysis workflow, including:

* Data Loading & Cleaning: It loads the raw Fact_Invoice.csv data, defines a schema, and handles missing values to ensure data quality.
* Exploratory Data Analysis (EDA): The notebook visualizes fundamental metrics such as the distribution of invoice amounts, popular payment methods, and monthly sales trends.
* Key Financial Metrics: It calculates important financial indicators like total revenue, average invoice amount, and the number of unique customers and vendors.
* Customer & Vendor Analysis: It analyzes customer behavior by identifying top spenders and categorizing them by purchase frequency. It also evaluates vendor performance based on invoice volume and payment processing times.
* Revenue & Growth Trends: The notebook calculates and visualizes monthly and quarterly revenue growth rates to identify business expansion and seasonal patterns.
* Discrepancy Reporting: It provides a summary of invoice discrepancies, including discounts, cancellations, and errors.
* SQL-Based Analysis: The notebook demonstrates how to perform all analyses using both the PySpark DataFrame API and Spark SQL for flexibility.

# Data Requirement
This notebook requires a single CSV file named Fact_Invoice.csv to be present in the same directory. The analysis is based on the schema and columns available in this dataset.

        ### Note: Analyses for product_category and regional_sales were requested but could not be performed as the required data columns were not present in the provided dataset.

# Setup and Usage
To run this notebook, you need a Python environment with PySpark and the necessary visualization libraries installed.

* Install Dependencies:

        pip install pyspark matplotlib seaborn

        Start a Spark Session:
  The notebook automatically initializes a local Spark session.

Run the Notebook:
Launch a Jupyter Notebook or JupyterLab server from your terminal and open invoice_analysis.ipynb.

        jupyter notebook

The notebook is designed to be executed cell-by-cell. Each section includes code, comments, and visualizations to help you understand the data and the analysis being performed.
# Screenshots of Notebook

* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/acf79d8696306d570ee3b38c8809a209d58e1e88/screenshots/Screenshot%20from%202025-09-26%2012-08-00.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/acf79d8696306d570ee3b38c8809a209d58e1e88/screenshots/Screenshot%20from%202025-09-26%2012-08-21.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-08-40.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-08-54.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-09-04.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-09-36.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-09-55.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-10-23.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-10-34.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-10-50.png)
* ![](https://github.com/MulukenSholaye/pyspark_receipt_analysis/blob/75263ad491c3a569720eb41d7431b0cd09bb8909/Screenshot%20from%202025-09-26%2012-11-11.png)
