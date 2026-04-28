# SQLForge — Smart Data Generator

SQLForge is a fully client-side smart SQL data generator that takes a `CREATE TABLE` statement and produces realistic `INSERT` statements. It natively supports formatting for MySQL, PostgreSQL, Oracle, SQL Server, and SQLite. 

## ✨ Features

* **100% Client-Side**: Everything runs securely in your browser, meaning no data is sent to external servers.
* **Multi-RDBMS Support**: Generates query syntax tailored for MySQL, PostgreSQL, Oracle, SQL Server, and SQLite.
* **High-Volume Generation**: Create anywhere from 1 to 5,000 realistic records per execution.
* **Smart Data Inference**: Automatically detects over 100 column name patterns (such as `first_name`, `email`, `ip`, `price`, `created_at`, `password`, `uuid`) and generates context-aware dummy data.
* **Primary Key Management**: Configure your Primary Keys to generate sequentially (1, 2, 3...), randomly, or skip them so the database handles them automatically.
* **Auto-Column Handling**: Easily toggle the inclusion of default or auto-generated columns (like `DEFAULT CURRENT_TIMESTAMP`).
* **Syntax Highlighting & Analysis**: Features color-coded SQL output and a dedicated Column Analysis panel showing detected patterns and constraints.
* **Export Options**: One-click copy to clipboard or direct download as a `.sql` file.
* **Built-in Templates**: Includes 10 ready-to-use example schemas like Users, Products, Orders, Employees, and Logs.

## 🚀 How to Use

1. Paste your `CREATE TABLE` statement into the input text area.
2. Select your target RDBMS from the dropdown menu.
3. Enter the number of records you wish to generate (up to 5000).
4. Configure your Primary Key mode (Sequential, Random, or Skip).
5. Click the **Generate** button or use the `Ctrl+Enter` keyboard shortcut.
6. Use the provided buttons to **Copy** the output or download it as a **.sql** file.

## 🛠️ Technology Stack

* **Core**: Vanilla HTML, CSS, and JavaScript completely contained within a single file.
* **Styling**: Tailwind CSS (via CDN) for rapid UI design.
* **Typography**: Space Grotesk for the user interface and JetBrains Mono for code blocks.
* **Icons**: Font Awesome 6.
* **Build Step**: None required; zero dependencies.