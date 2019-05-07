# csv_to_xlsx.py
Python scriptt to convert csv to xlsx (CLI + GUI)

PythonCSVtoXLSX (CLI + GUI)
Python script to convert CSV to XLSX.

Requirements
Python3+
xlsxwriter

Features
Create XLS sheets from CSV Files.
Define custom column names for the spreadsheet.
Skip rows with column length lesser than or greater the CSV header column length.
Custom XLS Filename for output.
Includes a tkinter GUI for batch conversion.

Usage
Make sure that all the requirements are satisfied -

Python3 & 
xlsxwriter

CLI: (Single file conversion)
Run the script - py csvxl.py
The script will then run you through all the steps that need to be followed in order to create the XLS document.
GUI: (Batch file conversion)
Run the GUI script - py GUI.py
Type the path to the CSV files folder, or select the folder by browsing.
Select whether or not the first line of the CSV is a header.

Note:
Press convert and wait. The script may take some time depending on how many files are being converted.
Logs are stored inside the logs/ directory, and the output is stored inside the output/ directory.
