ShoppingApp-fiori

A modern, responsive SAP Fiori application designed to provide a seamless retail shopping experience. This project demonstrates the implementation of SAP's Fiori Design Guidelines using SAPUI5 and integration with backend business logic.

🚀 Overview
The ShoppingApp-fiori is a web-based application that allows users to browse products, view detailed specifications, and manage a shopping cart. It serves as a practical implementation of Enterprise Application Development within the SAP BTP environment.

Key Features
Product Catalog: A dynamic list/grid view of available products with filtering and search capabilities.

Object Page: Detailed view of individual products including images, pricing, and descriptions.

Responsive Design: Optimized for Desktop, Tablet, and Mobile using the SAPUI5 Flexible Column Layout or SplitApp.

Cart Management: Ability to add/remove items and calculate total costs in real-time.

Mock/Live Data Integration: Seamless data binding using OData V2/V4 models.

🛠 Tech Stack
Frontend: SAPUI5 (OpenUI5), JavaScript, XML Views.

Tools: SAP Business Application Studio (BAS) / VS Code.

Framework: SAP Fiori Elements or Freestyle UI5.

Data Protocol: OData (Open Data Protocol).

Styling: SAP Horizon / Quartz Themes.

📂 Project Structure
Plaintext

ShoppingApp-fiori/
├── webapp/                 # Main application folder

│   ├── controller/         # Logic for the views

│   ├── view/               # XML Views (Main, Detail, etc.)

│   ├── i18n/               # Internationalization (translations)

│   ├── model/              # Data models and formatters

│   ├── test/               # Integration and Unit tests

│   ├── Component.js        # App configuration

│   └── manifest.json       # Application descriptor

├── ui5.yaml                # UI5 Tooling configuration

└── package.json            # Node.js dependencies

🏁 Getting Started
Clone the repository:

Bash

git clone https://github.com/your-username/ShoppingApp-fiori.git
Install dependencies:

Bash

npm install
Run the application locally:

Bash

ui5 serve

👤 Author
Jyoti Ranjan Rout

SAP BTP | CAPM | UI5 Fiori Developer# ShoppingApp-fiori

A responsive SAP Fiori retail app built with SAPUI5. This project features a dynamic product catalog, detailed object pages, and cart management using OData integration.  Tech: SAPUI5, JavaScript, XML Views, BTP.  Features: Search/Filter, Responsive UI, Data Binding. 
Developed by Jyoti Ranjan Rout.
