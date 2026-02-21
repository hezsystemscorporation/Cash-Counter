# **Cash Counter System**

You can start a demo program [here](https://hezsystemscorporation.github.io/Projects-Demos/cash_count.html). 

A lightweight, zero-install single-file Web application designed for rapid cash counting, handling loose banknotes and coins, and performing real-time foreign exchange conversions.

## **✨ Core Features**

* **All Denominations Supported (Local Cash)**: Built-in support for all CNY coins and banknotes from 1 Fen to 100 Yuan, clearly categorized.  
* **Smart Math**: No need for mental math or an extra calculator. Supports direct math expressions in the input field (e.g., 20+5), and the system automatically calculates 25 and updates the total instantly.  
* **Quick Append**: Click the \+ button on the right side of any row to quickly append newly counted quantities to the existing amount, which is perfect for handling messy cash.  
* **Live Foreign Exchange**: Supports logging multiple foreign currency entries (e.g., USD, EUR, JPY). The system automatically fetches live exchange rates via a public API and converts them to CNY, adding them to your total grand total.  
* **Export Report**: One-click copy of a text report containing all counting details, foreign exchange conversions, and the final grand total, making it easy to paste into Excel, chat apps, or emails for reporting.  
* **Privacy First**: All counted data is kept strictly in your browser's local memory and is destroyed upon refresh. No private financial data is ever uploaded or stored externally.

## **🚀 How to Use**

This project uses an extremely minimal architecture and **does not require** Node.js, NPM, or any local server environment.

1. Download the index.html file from this project.  
2. Double-click the file to open it in any modern browser (Chrome, Edge, Safari, Firefox).  
3. **Start Counting**: Enter the number of pieces/notes in the corresponding denomination input fields.  
4. **Add Foreign Currency**: Scroll to the bottom of the page, click Add Foreign Currency Record, select the currency, and enter the amount.  
5. **Export Data**: Click the Copy Report button in the top right corner and paste the results wherever you need them.

## **🛠️ Tech Stack**

* **HTML5 / JavaScript**: Native ES6+ syntax, with all logic encapsulated in a single file.  
* **Tailwind CSS (CDN)**: Uses utility classes to build a modern, responsive user interface adapted for mobile, tablet, and desktop devices.  
* **Lucide Icons (CDN)**: A lightweight, beautiful, open-source icon library.  
* **Exchange Rate API**: Utilizes the free public API provided by open.er-api.com to fetch live exchange rate data.

## **💡 Tips**

* If you open this tool in an offline environment without an internet connection, the foreign exchange module will automatically enable **Fallback Rates** mode to ensure basic conversion functionality remains available.  
* After typing an expression in the amount input field, press Enter or click on a blank space on the page, and the expression will automatically merge into the final calculated number.

## **📜 License & Copyright**

©Copyright 2026 Michael Hertz. All rights reserved.

Unauthorized commercial distribution or repackaging for profit of this code is strictly prohibited.
