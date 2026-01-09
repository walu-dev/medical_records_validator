# Medical Records Validation System

# Project Overview

The Medical Records Validation System is a Python-based application designed to validate medical patient records by checking their structure and data formats. It ensures that each record meets predefined rules and reports any missing or invalid fields clearly.

This project demonstrates skills in Python programming, data validation, regular expressions, and software engineering best practices.

# Objectives

Validate the structure of medical records

Detect missing or invalid fields

Enforce data integrity rules

Provide clear validation error messages

Prepare data for further analysis or processing

# Technologies Used

Python 3

Regular Expressions (re module)

Core Python data structures (lists, dictionaries)

# Validation Rules

Each medical record must contain the following fields:

Field Name	Validation Rule
patient_id	String, format P1234
age	Integer, must be ≥ 18
gender	Must be male or female
diagnosis	String or None
medications	List of strings
last_visit_id	String, format V1234
📂 Project Structure
medical-records-validator/
│
├── validator.py      # Core validation logic
├── data.py           # Sample medical records
├── README.md         # Project documentation

# How to Run the Project

Clone the repository:

git clone https://github.com/your-username/medical-records-validator.git


Navigate to the project folder:

cd medical-records-validator


Run the validator:

python validator.py

# Example Output

When invalid data is detected:

Unexpected format 'age: 15' at position 1.
Unexpected format 'patient_id: ABC' at position 2.


When all records are valid:

All medical records are valid.

# Future Improvements

Read medical records from a CSV file

Generate validation reports

Add unit tests

Add logging instead of print statements

Extend validation rules

# Author

Jonathan Enoch Walugembe
Computer Science Student | ALX Software Engineering Certified

# License

This project is open-source and available for educational and learning purposes.
