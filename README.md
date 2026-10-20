# BREW&MIST Café POS ☕

A modern, browser-based Point of Sale (POS) system designed to simplify café billing, product management, inventory tracking, and business analytics.

## Overview

BREW&MIST Café POS is a standalone web application built using HTML, CSS, and JavaScript. It provides an intuitive interface for managing café operations, processing customer bills, printing receipts, tracking sales, and analyzing product performance.

The application runs directly in a web browser without requiring a build system.

## Features

* **POS Billing:** Add products to orders, manage quantities, and calculate bills.
* **Receipt Printing:** Generate customer receipts with an 80 mm thermal-printer layout.
* **Sales History:** Maintain records of confirmed transactions.
* **Business Analytics:** Track revenue, completed bills, items sold, and average bill value.
* **Product Analytics:** Analyze product revenue, quantities sold, order frequency, and best-selling weekdays.
* **Inventory Management:** Manage product availability and stock information.
* **Product Management:** Add, edit, search, and organize menu products.
* **Date-Based Reporting:** Analyze business performance across selectable reporting periods.
* **Data Management:** Export and import JSON backups and export sales records to CSV.
* **Responsive Interface:** Access the application on desktop, tablet, and mobile browsers.

## Technology Stack

* HTML5
* CSS3
* JavaScript
* Browser Local Storage

## Getting Started

### Prerequisites

You need a modern web browser, such as Google Chrome or Microsoft Edge.

No additional software installation is required.

### Installation

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   ```

2. Open the project directory.

3. Open the main HTML file in your browser.

4. Start managing products, processing bills, and reviewing sales.

Alternatively, download the HTML file directly and open it in your browser.

## How It Works

1. Access the application and select the appropriate user role.
2. Browse the menu and add products to the current order.
3. Adjust quantities and review the bill.
4. Generate and print the receipt.
5. Confirm the transaction to record the completed sale.
6. Review sales history and business analytics.
7. Manage products and export backups when necessary.

## Data Storage

The application uses browser Local Storage to preserve application data across page reloads.

**Important:** Local Storage is not a substitute for a database or a reliable backup system. Data may be lost if browser storage is cleared or the browser profile is removed. Export backups regularly.

The application does not provide server-side data synchronization by default.

## Security Considerations

This project is designed as a client-side POS prototype. Browser-based authentication and role checks do not provide strong security because users with technical access can inspect or modify client-side code and stored data.

A production deployment should implement server-side authentication, authorization, database storage, and automated backups.

## Future Improvements

* Database integration for persistent business records.
* Secure server-side authentication and role-based access control.
* Cloud synchronization and automated backups.
* Enhanced sales forecasting and demand analysis.
* Advanced inventory alerts and stock management.
* Integration with payment gateways and mobile applications.

## Project Structure

```text
BREW-MIST-CAFE-POS/
├── Brew_Mist_Cafe_POS_Updated.html
└── README.md
```

The application is contained in a single HTML file, including its styles and JavaScript logic.

## License

Choose a license before distributing or allowing others to reuse this project. If you intend to make the source code publicly reusable, consider the MIT License.

---

**BREW&MIST Café POS** — Simplifying café billing and business management.
