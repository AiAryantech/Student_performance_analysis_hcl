# Student Performance Analysis - Data Previewer

A lightweight Python script built using `pandas` to interactively load and preview student performance datasets stored in Excel format.

## 📋 Overview

This tool allows users to quickly inspect the structure and initial records of student data files (`Raw_Student_Data.xlsx` and `Cleaned_Student_Data.xlsx`) directly from the console or a notebook environment like Google Colab.

## ✨ Features

* **Interactive File Selection:** Prompts the user to specify which dataset to load.
* **Custom Row Preview:** Lets the user define exactly how many top rows (`n`) they want to inspect.
* **Excel Support:** Uses `pandas.read_excel()` to seamlessly parse `.xlsx` files.

## 🛠️ Prerequisites

Make sure you have Python installed along with the required libraries:

```bash
pip install pandas openpyxl
