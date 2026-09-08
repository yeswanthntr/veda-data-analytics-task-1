# Veda Technology Internship - Task 1

## Data Cleaning and Preprocessing

### Dataset
Sample Superstore Dataset

### Objective
Clean and preprocess the raw Sample Superstore dataset by identifying and handling missing values, duplicate records, inconsistent formatting, and incorrect data types.

### Tools Used
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

### Data Quality Checks

The following checks were performed:

1. Dataset structure and data types
2. Missing values
3. Duplicate records
4. Text formatting
5. Postal Code data type
6. Final validation

### Cleaning Performed

- Checked all columns for missing values.
- No missing values were found.
- Identified 17 duplicate rows.
- Removed the 17 duplicate rows.
- Checked text columns for leading/trailing spaces.
- Converted Postal Code from numeric format to text format.
- Added leading zeros where required for postal-code consistency.
- Performed final validation after cleaning.

### Before Cleaning

- Rows: 9,994
- Columns: 13
- Duplicate rows: 17
- Missing values: 0

### After Cleaning

- Rows: 9,977
- Columns: 13
- Duplicate rows: 0
- Missing values: 0

### Output

`Cleaned_SampleSuperstore.csv`

### Project Files

- `SampleSuperstore.csv` - Original dataset
- `Cleaned_SampleSuperstore.csv` - Cleaned dataset
- `README.md` - Project documentation

### Conclusion

The Sample Superstore dataset was successfully cleaned and validated using Python and Pandas. Duplicate records were removed, the Postal Code field was standardized as a text identifier, and the final dataset was verified for missing values and duplicates.
