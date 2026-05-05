# IT3040 Assignment 1 - Transliteration Accuracy Testing

## Student Details

Registration Number: IT23600966  
Module: IT3040 - ITPM  
Assignment: Assignment 1  
Option: Option 1 - Transliteration Accuracy Testing  

## Project Description

This project automates testing for the Pixelssuite Chat Translator website.

Website tested:  
https://www.pixelssuite.com/chat-translator

The automation reads Singlish inputs from the Excel file, enters them into the website, captures the Sinhala output, and updates the Excel file with the actual output and test status.

## Tools Used

- Python
- Playwright
- OpenPyXL
- Microsoft Excel




## Install Dependencies

Open Command Prompt or PowerShell in the project folder and run these commands:

```bash
py -m pip install -U pip
py -m pip install playwright openpyxl
py -m playwright install
```

## Prepare Excel File

Close the Excel file before running the automation.


## What the Script Does

The script opens the Pixelssuite Chat Translator website, reads each Singlish input from the Excel file, enters the input into the website, captures the Sinhala output, saves it in the `Actual output` column, compares it with the `Expected output`, updates the `Status` column as PASS or FAIL, and saves the Excel file automatically.

## After Running

After the automation finishes, open the Excel file and check the results.

Then complete these two columns manually:

```text
Singlish input types covered
Evidence or rationale for the input type covered
```

## Notes

- Keep the Excel file closed while running the script.
- Make sure the internet connection is working.
- Do not change the Excel column names.
- Press `CTRL + C` in the terminal to stop the script after checking the browser.
