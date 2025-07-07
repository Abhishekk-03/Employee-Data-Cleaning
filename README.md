# Employee Data Cleaning Project (Pandas + NumPy)
This project demonstrates how to clean and preprocess raw employee data using Pandas and NumPy in Python. The final cleaned dataset is saved as a CSV file and can be used for further analysis or reporting.

**Tasks Performed:**

- Loading the Dataset
*Imported the employee dataset using pandas.read_csv()*
  
- Checking for Missing Values
Identified null or missing values in the dataset.

- Filling Missing Values
Replaced missing salaries with the average salary.
Replaced missing performance ratings with the median rating.

- Handling Infinite Values
Replaced infinite values with NaN to maintain consistency.

- Removing Duplicate Rows

	•	Dropped all duplicate entries from the dataset to ensure data uniqueness.

	6.	Replacing Negative Salaries

	•	Converted all negative salary values to their absolute values (positive).

	7.	Removing Unnecessarily High Salaries (Outliers)

	•	Calculated the mean and standard deviation of salary.

	•	Removed salaries that were far above the normal range (outliers).

	8.	Saving Cleaned Data

	•	Exported the cleaned DataFrame to a new CSV file for further use.

⸻

📁 Output:

	•	A cleaned and structured CSV file ready for analysis.
 
