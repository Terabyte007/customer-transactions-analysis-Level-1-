# Customer Transactions Dataset – Project Report

## Task Objective
The objective was to **clean, analyze, and visualize** a customer transactions dataset to uncover demographic and financial patterns.  
Key goals included:
- Ensuring data consistency (DOB, gender, transaction dates/times).
- Performing **exploratory data analysis (EDA)**.
- Generating **visualizations** for insights.

---

## 🛠️ Steps Taken
- **[Data Cleaning](ca://s?q=Explain_data_cleaning_steps)**
  - Handled missing values (removed or imputed).
  - Removed duplicate records.
  - Standardized formats for dates, times, categorical values, and numeric fields.
  - Resolved inconsistent `CustomerDOB` and `CustGender` by keeping the most frequent/earliest values.
  - Normalized gender labels to **Male/Female** only.

- **[Exploratory Analysis](ca://s?q=Perform_exploratory_data_analysis)**
  - Computed summary statistics (min, max, mean, median, mode, std) for account balances, transaction amounts, and customer ages.
  - Created age groups for demographic segmentation.

- **[Data Visualization](ca://s?q=Show_data_visualization_examples)**
  - Bar charts: transactions by age group, average transaction amount by age group.
  - Histograms: customer age distribution, monthly transaction counts.
  - Line charts: average and total transaction amounts per month.
  - Boxplots: account balance distribution by age group.
  - Scatterplots: relationships between age, balance, and transaction amount.
  - Correlation heatmap of numerical features.

---

## Key Insights
- **Age vs Balance**: Older customers tend to hold slightly higher balances, though most balances remain modest.
- **Wealth Concentration**: A few middle-aged customers (35–54) hold extremely high balances, creating a long-tailed distribution.
- **Transaction Amounts**: Spending size is largely independent of age or account balance.
- **Monthly Trends**: Transactions occur consistently across months, with no strong seasonal spikes.
- **Demographics**: Diverse age groups are active, but younger customers (<25) show lower balances and spending.
- **Gender Analysis**: Both Male and Female customers transact regularly, with similar average amounts.

---

## Output
- **Source Dataset**: [Download from Google Drive](https://drive.google.com/file/d/1TwyuJh2yNQG3iAhU9seg0B2PPIIdM9Bv/view?usp=sharing)  
- **Cleaned Dataset**: [Download from Google Drive](https://drive.google.com/file/d/1cognDjJly5arK3Y-rUrtO_0qRdvMGiNH/view?usp=sharing)  
- **Visualizations**: Generated directly within the Python notebook/script (`customer_transactions_analysis Level 1`).  
  Run the file to reproduce charts (bar charts, line charts, histograms, boxplots, scatterplots, heatmaps).

---

## ⚙️ Usage
1. Download the dataset(s) from the links above.  
2. Place them in a `/data/` folder in your project directory.  
3. Run the Python notebook/script to reproduce cleaning, analysis, and visualizations.  
4. Results will be exported as CSV and PNG files.
