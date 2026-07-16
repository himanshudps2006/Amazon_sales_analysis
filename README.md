# Amazon Sales Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on Amazon sales data using Python. The objective is to identify customer purchasing patterns, product preferences, sales distribution, and shipping trends to derive useful business insights.

The analysis has been carried out using Jupyter Notebook with various Python data analysis and visualization libraries.

---

## Dataset

- Dataset: Amazon Sale Report.csv
- File included in this repository.
- Contains information about:
  - Product categories
  - Quantity sold
  - Product sizes
  - Shipping details
  - Courier status
  - Customer location (state-wise)
  - B2B and retailer sales
  - Sales amount and dates

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Structure

```
Amazon-Sales-Analysis/
│
├── Amazon Sales Analysis.ipynb
├── Amazon Sale Report.csv
├── README.md
└── Images (optional for plots)
```

---

## Data Cleaning Process

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Removed unnecessary columns.
- Checked for missing values.
- Dropped null values.
- Converted postal code into integer format.
- Converted the Date column into datetime format.
- Verified data types and column information.

---

## Exploratory Data Analysis

The project includes the following analyses:

### Product Size Analysis

- Count plot of product sizes.
- Quantity sold by size.
- Identification of the most purchased size.

### Courier Status Analysis

- Distribution of shipped and courier order statuses.
- Shipping trends visualization.

### Product Category Analysis

- Histogram of product categories.
- Identification of the most popular product categories.

### B2B Analysis

- Pie chart representing:
  - B2B customers
  - Retail customers

### Category vs Size Analysis

- Scatter plot showing relationships between:
  - Product category
  - Product size

### State-wise Sales Analysis

- Distribution of orders across states.
- Top 10 states based on sales volume.

---

## Key Insights

The analysis revealed that:

- M-size products are the most preferred among customers.
- T-shirts are the highest-selling product category.
- Most orders are successfully shipped through couriers.
- Maharashtra contributes the highest number of orders.
- Approximately 99.2% of buyers are retailers.
- Only a small percentage of customers are B2B buyers.
- Amazon fulfils a large portion of customer orders efficiently.

---

## Visualizations Used

The project uses:

- Count Plots
- Bar Plots
- Histograms
- Pie Charts
- Scatter Plots

These visualizations help in understanding customer behavior and sales trends effectively.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Amazon-Sales-Analysis.git
```

Move to the project directory:

```bash
cd Amazon-Sales-Analysis
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
Amazon Sales Analysis.ipynb
```

Run all the cells to reproduce the analysis and visualizations.

---

## Future Improvements

- Perform sales forecasting.
- Build an interactive dashboard.
- Analyze monthly and yearly sales trends.
- Create product recommendation insights.
- Perform customer segmentation analysis.

---

## Conclusion

This Amazon Sales Analysis project demonstrates how data cleaning, exploratory data analysis, and visualization techniques can be used to uncover valuable business insights from sales data. The findings can help businesses better understand customer preferences and improve decision-making.

---

## Author

**Piyush Kumar Gupta**

If you found this project useful, feel free to star the repository.
