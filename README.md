# Exporting React Gantt Chart with Complete Customization

A React sample app demonstrating Syncfusion Gantt export to PDF, Excel, and CSV.

## Overview

This project shows a Create React App example using `@syncfusion/ej2-react-gantt` and toolbar-driven export actions.

## Features

- PDF export with custom task and progress styling
- Excel export with a custom header, footer, and theme
- CSV export support
- Toolbar buttons for `PdfExport`, `ExcelExport`, and `CsvExport`
- Sample task data loaded from `src/data.js`

## Dependencies

- `react` ^17.0.1
- `react-dom` ^17.0.1
- `react-scripts` 4.0.1
- `typescript` ^4.1.3
- `@syncfusion/ej2-react-gantt` ^18.4.42

## Getting started

1. Open the project folder in Visual Studio Code.
2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Visit `http://localhost:3000`.

## Usage

The app uses `toolbarClick` in `src/App.tsx` to export:

- PDF with styled task bars
- Excel with a custom report header and footer
- CSV export

## Notes

- Built with Create React App and TypeScript.
- Customize export settings in `src/App.tsx`.

## Scripts

- `npm start`
- `npm build`
- `npm test`
- `npm eject`
