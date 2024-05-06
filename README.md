# Customer-loyalty-Reward-system

This Google Apps Script project is designed to manage customer purchases based on id input/scanned QR codes in a Google Sheets document to aid reward and customer retention. The system increments the purchase amount for customers whenever a valid id is inputted or QR code is scanned.

## Features

- **QR Code Scanning:** Scan QR codes in column A of 'CODES SHEET' in the Google Sheets document.
- **Manual Input:** Manually input codes present in the Customer database in column A of the 'CODES SHEET' if no scanner device is available.
- **Customer Database:** Maintain a database of customers and their purchase amounts.
- **Incremental Purchase:** Increase the purchase amount for customers with each valid id input or scan of QR code.

## Getting Started

### Setup Google Sheets:

1. Create a new Google Sheets document or use an existing one.
2. Ensure there is a sheet named 'CustomerDatabase' where your data is organized with QR codes in column A and purchase amounts in column B (or adjust column references in the script).
3. Ensure you have another sheet called 'CODES' where all customer codes can be inputted for the count or where all scans can reflect.

### Attach Script:

1. Open the Google Sheets document.
2. Go to Extensions > Apps Script to open the script editor.
3. Copy and paste the provided Google Apps Script code into the editor.

### Save and Run:

1. Save the script in the editor.
2. Edit any cell in column A to trigger the script.
3. Verify that the script increments purchase amounts correctly.

## Notes

- Id/QR code can only be 6 values maximum, which can be adjusted.
- Make sure to adjust sheet names, column references, and any specific logic as needed for your data structure.
- Test the system with sample data to ensure proper functionality.
- Monitor the script logs (View > Logs) for debugging and error checking.
