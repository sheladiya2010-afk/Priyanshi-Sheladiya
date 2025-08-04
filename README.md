# Marketing Campaign Dataset Cleaning

This project involves cleaning a raw marketing dataset to make it ready for analysis or modeling. Below are the steps that were performed:

### 📥 Data Loading
- Loaded `marketing_campaign.csv` (tab-separated) using Pandas.

### 🧹 Data Cleaning
- **Missing Values**:
  - Filled missing values in the `Income` column using the median.

- **Duplicates**:
  - Checked and removed any duplicate records.

- **Text Standardization**:
  - Cleaned `Education` and `Marital_Status` columns by stripping extra spaces and capitalizing.

- **Date Formatting**:
  - Converted `Dt_Customer` to proper `datetime` format.

- **Column Renaming**:
  - Renamed `Dt_Customer` to `Registration_Date`.
  - Replaced spaces in column names with underscores for easier access in code.

- **Data Type Optimization**:
  - Applied `convert_dtypes()` to improve memory efficiency and handle nullable types.

### 💾 Output
- Cleaned dataset saved as `marketing_campaign_cleaned.csv`.

### ✅ Result
The dataset is now ready for analysis, modeling, or visualization with consistent formatting, no missing values, and clean column naming.
