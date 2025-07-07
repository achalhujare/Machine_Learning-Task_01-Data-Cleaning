Import Libraries

Loaded essential libraries like pandas, numpy.

Load Dataset

Used pandas.read_csv() to read the CSV file into a DataFrame.

Initial Inspection

Used .head(), .info(), .describe() to understand data structure and summary.

Handle Missing Values

Checked for null values using .isnull().sum().

Filled or dropped missing values using .fillna() or .dropna().

Remove Duplicates

Used .duplicated() and .drop_duplicates() to remove repeated rows.

Data Type Conversion

Converted data types (e.g., string to datetime, float to int) using .astype() or pd.to_datetime().

Outlier Detection & Removal

Identified outliers using statistical methods (like IQR or Z-score).

Removed or treated outliers if needed.

Standardize or Normalize Data

Applied scaling techniques for numerical columns using MinMaxScaler or similar.

Fix Inconsistent Data

Cleaned and standardized categorical entries (e.g., "Male", "male", "M" → "Male").

Save Cleaned Data

Exported the cleaned dataset using .to_csv().
