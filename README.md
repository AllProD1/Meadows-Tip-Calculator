# Meadows Tip Distributor

## Overview

The Meadows Tip Distributor is a tool designed to simplify the process of distributing employee tips at The Meadows Ice Cream. It combines transaction data from Square with employee shift schedules from When I Work to calculate how tips should be distributed based on which employees were working when each tip was received.

## Download

Download the Meadows Tip Distributor and run it directly in your web browser. No installation is required.

[Right-click here and select "Save Link As..." to download the HTML file](https://raw.githubusercontent.com/AllProD1/Meadows-Tip-Calculator/refs/heads/main/meadows_tip_distributor_v8.html)

<a href="[path/to/your/file.html](AllProD1/Meadows-Tip-Calculator/refs/heads/main/meadows_tip_distributor_v8.html)" download>Click here to download the HTML file</a>


After downloading, open the `.html` file in your web browser to use the application.


## Features

- **Automated tip distribution:** Allocates tips among employees who were on shift when each tip was received.
- **Refund handling:** Automatically accounts for refunds when calculating the net tip total.
- **Shift schedule integration:** Uses employee timesheets to determine who was working at the time of each transaction.
- **Owner tip allocation:** Assigns tips received when no employees were clocked in, or when a tip's timestamp cannot be read, to the designated owner.
- **Results summary:** Displays tip totals, employee breakdowns, number of tips received, shifts worked, and each employee's share.
- **CSV export:** Allows the calculated tip distribution to be exported for recordkeeping and further use.

## How It Works

The application uses a simple three-step process:

1. **Upload Square transactions:** Import a CSV or Excel export containing transaction dates, times, and tip amounts.
2. **Upload employee schedules:** Import a CSV or Excel timesheet export from When I Work covering the relevant pay period.
3. **Calculate and export:** The application matches tips to employees working at the time of each transaction, accounts for refunds, displays the results, and allows the final breakdown to be exported as a CSV file.

When multiple employees are working at the time a tip is received, the tip is divided equally among those employees.

## Usage Notes

- Both exports should cover the same pay period.
- Review any warnings about missing timestamps, unmatched refunds, or shift data that could not be processed.
- Verify the calculated totals before using them for payroll or tip records.
- The results can be exported to CSV for additional review and recordkeeping.

## Technology

The application runs in a web browser and uses JavaScript, HTML, and CSS. It uses the SheetJS library to read Excel files and supports CSV imports and exports.

## Disclaimer

This tool is intended to assist with tip distribution and recordkeeping. Review the results for accuracy before using them for payroll or other financial records.

## Acknowldgement

This code was completely ai generated. I used this as an experience to explore problem solving with ai. This was a real problem that needed a solution. I engineered the
prompts to lead to an accurate solution that was well tested. This code has been operational now for 5 months with no bugs or errors. The owners who commissioned me to do
this project wanted ai to help solve the problem and it did. Also, I know that this now saves the employer 8 hours per pay period being a valuable asset to the company now.
