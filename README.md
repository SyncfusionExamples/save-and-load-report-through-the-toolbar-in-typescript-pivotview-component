# 📊 Save & Load Reports in TypeScript PivotView Component

[![License](https://img.shields.io/badge/license-SEE%20LICENSE-blue.svg)](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf) [![TypeScript](https://img.shields.io/badge/TypeScript-Latest-3178C6.svg)](https://www.typescriptlang.org/) [![Syncfusion EJ2](https://img.shields.io/badge/Syncfusion%20EJ2-Latest-0078D4.svg)](https://www.syncfusion.com/)

> **Production-ready TypeScript implementation demonstrating toolbar-based report persistence in Syncfusion Essential JS 2 PivotView** — save and restore pivot table configurations with seamless JSON export and file import integration.

## 🎯 Overview

This repository provides a complete, production-ready implementation for **saving and loading pivot table reports** using Syncfusion's Essential JS 2 PivotView component with full TypeScript support. Perfect for building business intelligence dashboards, financial reporting tools, and analytics applications requiring persistent pivot table configuration management.

## ✨ Key Features

- ✅ **Save Reports**: Export pivot configurations to JSON format through intuitive toolbar buttons
- ✅ **Load Reports**: Import and restore saved JSON report configurations with single-click operation
- ✅ **Toolbar Integration**: Seamless report management UI within EJ2 toolbar component
- ✅ **TypeScript Support**: Fully typed codebase ensuring robust development and type safety
- ✅ **Syncfusion EJ2**: Leverages robust, feature-rich PivotView with calculated fields and field list
- ✅ **File Management**: Native file import/export for easy report sharing and backup
- ✅ **Cross-Browser Compatible**: Works across Chrome, Firefox, Safari, and Edge

## 🛠 Prerequisites & Requirements

- **Node.js**: Version 12.0 or later from [nodejs.org](https://nodejs.org/en/download)
- **npm**: Included with Node.js for dependency management
- **Visual Studio Code**: Latest version recommended
- **TypeScript Knowledge**: Familiarity with ES6+ and TypeScript syntax
- **Syncfusion License**: Community or commercial license for production use

## 📦 Installation & Setup

1. **Clone Repository**
   ```bash
   git clone https://github.com/SyncfusionExamples/save-and-load-report-through-the-toolbar-in-typescript-pivotview-component
   cd save-and-load-report-through-the-toolbar-in-typescript-pivotview-component
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Build & Run**
   ```bash
   npm start
   ```

4. **Access Application**: Open `http://localhost:8080` in your browser

## 🚀 Quick Start Usage

Once the application is running:

- **View Data**: Pivot table displays sample datasource with countries, products, and sales
- **Save Report**: Click toolbar "Save" button to export current pivot configuration as JSON
- **Load Report**: Use "Open" button to select previously saved JSON file and restore configuration
- **Modify & Re-save**: Adjust pivot layout, add calculated fields, and save as new report

## 🗂 Project Structure

```
├── src/
│   ├── index.html              # Application template & PivotView markup
│   ├── app/
│   │   ├── app.ts              # PivotView initialization & report management
│   │   └── datasource.ts        # Sample JSON datasource
│   └── styles/
│       └── styles.css           # Component styling
├── package.json                 # Dependencies and scripts
├── tsconfig.json               # TypeScript configuration
└── webpack.config.js           # Webpack bundler configuration
```

## 🔧 Core Implementation

The application uses Syncfusion EJ2 PivotView with:

- **Toolbar Integration**: Save and open buttons for report management
- **Data Binding**: Dynamic datasource with multiple dimensions
- **Calculated Fields**: Extended analytics capabilities
- **JSON Persistence**: Report export/import via file system

## 📚 Resources

- [Syncfusion EJ2 PivotView Documentation](https://www.syncfusion.com/javascript-ui-controls/js-pivot-table)
- [TypeScript Official Guide](https://www.typescriptlang.org/docs/)
- [Webpack Configuration](https://webpack.js.org/)

## 📄 License

This project is licensed under the **Syncfusion Community License**. See [Syncfusion License](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf) for details.

## 🆘 Support

For issues or questions:
- 📧 Open an issue on GitHub
- 💬 Visit [Syncfusion support forums](https://www.syncfusion.com/forums)
- 🌐 Check [Syncfusion documentation](https://www.syncfusion.com/javascript-ui-controls/)
