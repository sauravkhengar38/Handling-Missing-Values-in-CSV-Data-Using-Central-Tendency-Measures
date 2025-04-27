🔹 Project Overview:
I developed a Python script to handle missing values in a CSV data file using the fillna() method from the pandas library.

🔹 Steps Followed:
📂 1. Loaded the dataset into a DataFrame.
🔍 2. Identified columns with missing data.
🛠️ 3. Handled missing values using three central tendency measures:

📈 Mean (for normally distributed numerical data)

📊 Median (for skewed numerical data)

🗂️ Mode (for categorical data)

🔹 Methodology:

➡️ For numerical columns, missing values were filled with either the mean or median, depending on the distribution of data.

➡️ For categorical columns, missing entries were filled using the mode value.

🔹 Result:
✅ This method preserved the statistical integrity of the dataset, ensuring that future data analysis and machine learning models could perform accurately without being affected by missing values.
