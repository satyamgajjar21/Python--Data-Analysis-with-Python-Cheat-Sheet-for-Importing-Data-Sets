# Data Analysis with Python: Cheat Sheet for Importing Data Sets

This cheat sheet provides quick reference commands to import and explore datasets in Python using the pandas library.

---

## Table of Contents

- [Read CSV Dataset](#read-csv-dataset)  
- [Print First Few Entries](#print-first-few-entries)  
- [Print Last Few Entries](#print-last-few-entries)  
- [Assign Header Names](#assign-header-names)  
- [Replace "?" with NaN](#replace-with-nan)  
- [Retrieve Data Types](#retrieve-data-types)  
- [Retrieve Statistical Description](#retrieve-statistical-description)  
- [Retrieve Dataset Summary](#retrieve-dataset-summary)  
- [Save DataFrame to CSV](#save-dataframe-to-csv)  

---

## Read CSV Dataset

Read a CSV file into a pandas DataFrame.

```python
# Load without header
df = pd.read_csv(<CSV_path>, header=None)

# Load using first row as header
df = pd.read_csv(<CSV_path>, header=0)
