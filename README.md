# Sales-Data
## Sales Data Cleaning and Preprocessing
#### This project contains a Jupyter Notebook that performs **data cleaning and preprocessing** on a sales dataset (`Sales-Export_2019-2020.csv`). The goal is to prepare the data for further analysis or visualization.

1. **Imports Libraries**
   - Uses `pandas`, `numpy`, and suppresses warnings for a clean environment.

2. **Loads the Dataset**
   - Reads `Sales-Export_2019-2020.csv` using `pandas.read_csv`.

3. **Performs Initial Exploration**
   - Displays the first and last few rows.
   - Checks data types, missing values, and duplicates.

4. **Cleans the Data**
   - Title-cases relevant text columns: `country`, `customer_name`, `sales_manager`, `sales_rep`.
   - Converts the `date` column from object to `datetime`.
   - Cleans and converts `order_value_EUR` from object to numeric.
   - Renames columns with extra spaces (eg: cost, order_vale_EUR)
