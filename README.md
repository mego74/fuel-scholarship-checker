# FUEL Checker

## What it does

- Reads the Fellowship workbook and Master workbook from local file uploads.
- Uses `EMPL ID` to match students.
- Routes students by `Total Offered Amount`
- Highlights matching rows yellow in the Master workbook.
- Highlights missing rows red in the Fellowship workbook.
- Downloads the highlighted workbooks and a summary workbook.

No Excel files are uploaded to a server.

## Dependencies

The page includes these browser libraries in `vendor/` so the app can run from GitHub Pages without a backend:

- ExcelJS `4.4.0`
- JSZip `3.10.1`
