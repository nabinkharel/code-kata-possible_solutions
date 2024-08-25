# Data Engineering Tasks

## Problem 1: Parse Fixed-Width File

### Task Description
- **Generate a Fixed-Width File:** Using a provided specification (`spec.json`), generate a fixed-width file. The offset (length) provided in the spec file represents the maximum number of characters each field can hold.
- **Implement a Parser:** Create a parser that can read the fixed-width file and convert it into a delimited file, such as CSV.
- **Constraints:** 
  - **No External Libraries:** Do not use Python libraries like `pandas` for parsing. The task should be completed using the Python standard library.
  - **Language Choices:** You may use Python or Scala for this task.

### Assumptions
- The `spec.json` file provides the column names and the maximum number of characters each column can hold in the file.
- There will be some data available to parse, which will be used to create a new file with the specified column widths. This file will then be converted from a `.txt` format to a CSV file.

## Problem 2: Data Processing

### Task Description
- **Generate a CSV File:** Create a CSV file containing the following columns: `first_name`, `last_name`, `address`, `date_of_birth`.
- **Anonymize Data:** Process the CSV file to anonymize the data in the `first_name`, `last_name`, and `address` columns.
- **Scalability:**
  - **2GB CSV File:** Ensure that the process can handle a 2GB CSV file on a typical laptop.
  - **Large Datasets:** Demonstrate that the same process can be adapted to work on even larger datasets, potentially using a distributed computing platform.




