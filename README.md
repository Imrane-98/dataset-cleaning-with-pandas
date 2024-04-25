# dataset-cleaning-with-pandas<br>  

This repository contains scripts and documentation for cleaning a dataset using Python's Pandas library. The primary focus is on common data cleaning operations to ensure a clean and reliable dataset for further analysis or use in machine learning models.   

The following tasks are covered:

- Removing Duplicates: Detects and removes duplicate rows to ensure data integrity.

- Deleting Irrelevant Columns: Removes a specified column ("Not_Useful_Column") that is not needed for analysis.

- Applying Strip Operations: Cleans up whitespace and other unwanted characters from specific columns.

- Sanitizing Phone Numbers: Removes all characters from the "Phone_Number" column that are not alphanumeric (a-z, A-Z, 0-9) and formats them as xxx-xxx-xxxx.<br>

- Replacing Incorrect Values: Replaces invalid occurrences of "nan--" and "Na--" with an empty string in specific columns.<br>

- Splitting Address Data: Splits the "Address" column into three new columns ("Street_Address", "State", "Zip_Code") using a comma as a delimiter with a maximum of two splits.<br>

- Additional cleaning operations may include handling missing values, encoding categorical data, removing outliers, and ensuring proper data types for analysis.<br>

--------

 **Contents**

Data Cleaning Script: The main script that performs the cleaning operations described above.

Sample Data: An example dataset demonstrating the data before and after cleaning.

Documentation: Detailed explanations of the cleaning steps, along with comments explaining the code.

---------

**Getting Started**

To get started with this repository, ensure you have Python and Pandas installed on your system. You can run the data cleaning script with the following command:


1- Copy code python data_cleaning_script.py  

2- Load Data: Customer Call List.xlsx

3- Execute Cleaning: Run the script to apply the described cleaning operations.

4- Review Results: Check the cleaned dataset to ensure it meets your requirements.

----------

**Contributing**

Contributions are welcome! If you'd like to suggest improvements, add new cleaning operations, or report issues, please create a pull request or open an issue in this repository.

