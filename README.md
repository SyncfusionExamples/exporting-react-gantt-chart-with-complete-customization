# Exporting React Gantt Chart with Complete Customization

A React sample application demonstrating how to export a [React Gantt Chart]((https://www.syncfusion.com/react-components/react-gantt-chart)) to PDF, Excel, and CSV formats using built-in toolbar actions and export APIs.

## Repository Description

This repository contains a React example that showcases export functionality for the Syncfusion Gantt Chart, including PDF, Excel, and CSV outputs triggered through toolbar interactions.

## Overview

The sample focuses on configuring a Gantt chart with multiple export options. It demonstrates how toolbar actions can be wired to export APIs and how export settings can be adjusted in code to control formatting and output behavior.

## Features

- PDF export with customized taskbar and progress styling
- Excel export with configurable header, footer, and theming
- CSV export support for task data
- Toolbar buttons for `PdfExport`, `ExcelExport`, and `CsvExport`
- Task data loaded from a local data source

## Getting Started

### Prerequisites

- Node.js (LTS or later)
- npm

### Installation

Install project dependencies:


   ```bash
   npm install
   ```

Start the development server:

   ```bash
   npm start
   ```

Visit `http://localhost:3000`.

## Usage

- Export actions are handled using the `toolbarClick` event in the main component file.
- PDF export applies custom styling to taskbars and progress indicators.
- Excel export generates a report with customized headers and footers.
- Export behavior can be modified within the component configuration.

## Related Links

- [Explore React Gantt Chart](https://www.syncfusion.com/react-components/react-gantt-chart)
- [Gantt Chart Feature Overview](https://ej2.syncfusion.com/react/documentation/gantt/overview)
- [React Gantt Chart Getting Started Guide](https://ej2.syncfusion.com/react/documentation/gantt/getting-started)
- [React Gantt API Documentation](https://ej2.syncfusion.com/react/documentation/api/gantt/)
- [React Gantt Chart Live Demos and Examples](https://ej2.syncfusion.com/react/demos/#/tailwind3/gantt/exporting)
