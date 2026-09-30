# SDC310 Week 4 Performance Assignment - PHP MVC Web Application

This repository contains a PHP web application architected using the **Model-View-Controller (MVC)** software design pattern. The application connects to a MySQL database (`sdc310_wk4pa`) using PDO and dynamically renders product records in an HTML interface.

---

## 🏗️ Architecture & Project Structure

The project strictly follows the MVC design pattern to separate concerns:

```text
sdc310_week4_pa/
├── .vscode/
│   └── launch.json            # VS Code run/debug configuration
├── model/
│   └── database.php           # Model: PDO database connection class
├── controller/
│   └── product_controller.php # Controller: Business logic & data fetching
├── view/
│   └── product_list.php       # View: HTML template & UI presentation
└── README.md                  # Project documentation
