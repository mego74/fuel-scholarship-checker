# FUEL Scholarship Checker

Static GitHub Pages version of the FUEL Scholarship Checker.

## What it does

- Runs completely in the browser.
- Reads the Fellowship workbook and Master workbook from local file uploads.
- Uses `EMPL ID` to match students.
- Routes students by `Total Offered Amount`:
  - `$15,000` routes to the selected 15k master tab.
  - `$20,000` routes to the selected 20k master tab.
- Highlights matching rows yellow in the Master workbook.
- Highlights missing rows red in the Fellowship workbook.
- Downloads the highlighted workbooks and a summary workbook.

No Excel files are uploaded to a server.

## GitHub Pages setup

1. Create a new GitHub repository.
2. Upload `index.html` and the `vendor/` folder from this folder to the repository root.
3. In GitHub, go to `Settings` > `Pages`.
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. Open the GitHub Pages URL after GitHub finishes deploying.

## Dependencies

The page includes these browser libraries in `vendor/` so the app can run from GitHub Pages without a backend:

- ExcelJS `4.4.0`
- JSZip `3.10.1`
