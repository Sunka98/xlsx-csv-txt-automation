# xlsx-csv-txt-automation
# Excel to CSV to TXT Automation Script

## Overview
This Bash script automates the conversion of **Excel (.xlsx) files to CSV**, followed by **splitting the CSV files into structured TXT files** with selected columns.

## Features
- Converts all `.xlsx` files in a given directory to `.csv` format using a Python script (`exceltocsv.py`).
- Extracts specific columns from the CSV files and saves them as `.txt` files.
- Organizes output files into structured directories.
- Optionally moves processed Excel files to a separate folder.

## Prerequisites
- **Python 3** must be installed.
- A Python script `exceltocsv.py` must exist in the same directory (or be accessible in `PATH`).
- The script uses standard UNIX tools: `awk`, `tr`, and `cat`.