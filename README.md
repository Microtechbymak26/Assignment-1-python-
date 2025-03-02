# File Converter & Cleaner

A Streamlit application for processing, cleaning, and converting CSV and Excel files.

## Features

- Upload CSV and Excel (.xlsx) files
- Process multiple files simultaneously
- Data Cleaning:
  - Remove duplicate records
  - Fill missing values with mean values
- Column selection
- Data visualization (bar charts for numeric columns)
- File conversion:
  - CSV to Excel
  - Excel to CSV

## Installation

1. Install Python
2. Install required packages:
```bash
pip install streamlit pandas openpyxl
```

## How to Use

1. Run the following command in terminal:
```bash
streamlit run app.py
```

2. The application will open in your browser

3. Click "Upload file" button to select your CSV or Excel file

4. Use available options:
   - Remove Duplicates: To remove duplicate records
   - Fill missing Values: To fill empty cells
   - Select Columns: To choose specific columns
   - Show Charts: To view data visualization

5. Finally, download the file in desired format (CSV or Excel)

## Requirements

- Python 3.6+
- streamlit
- pandas
- openpyxl 