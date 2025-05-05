# Inventory Management System (IMS)

Welcome to the **Inventory Management System (IMS)**! This project is designed to help users manage and track inventory in a warehouse, including product movements, warehouse management, and reporting.

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Demo Video](#demo-video)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)


## About the Project
The **Inventory Management System (IMS)** is a web-based application built using **Flask**. The purpose of the system is to help manage product inventories in warehouses, track movements, and generate reports.

Key functionalities of the system include:
- Managing products, categories, and warehouses.
- Adding, updating, and transferring stock between warehouses.
- Viewing reports on product movement and inventory levels.

## Features
- **Dashboard**: View overall statistics and quick access to different sections.
- **Product Management**: Add, edit, and delete products.
- **Warehouse Management**: Create and manage warehouses.
- **Product Movement**: Track and manage movements such as sales, purchases, and transfers between warehouses.
- **Reports**: Generate detailed reports on stock levels and movements.

## Installation
Follow these steps to set up the Inventory Management System on your local machine:

### 1. Clone the repository
```bash
git clone https://github.com/Santhosh1015/Inventory_Management_System.git
cd Inventory_Management_System
```

### 2. Set up a virtual environment
```bash
python -m venv venv
```

### 3. Activate the virtual environment
Windows:
```bash
.\venv\Scripts\activate
```

Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install dependencies
```bash
pip install -r requirements.txt
```

### 5. Run the application
```bash
python app.py
```

## How to Use
- Log in to the application to access the dashboard.
- Navigate to different sections using the sidebar:
  - Warehouse: Manage your warehouse locations.
  - Products: Add, view, and edit products.
  - Movement: Track product transfers between warehouses.
  - Reports: View detailed inventory and movement reports.
- Use the forms to add or update products, warehouses, and movement records.

## Demo Video
Check out the demo of the Inventory Management System:
Demo Video Link (Insert demo video link here)

## Screenshots
### Landing Page
The landing page provides an overview of the system and a navigation menu to access different features.

### Dashboard
The dashboard shows a summary of warehouse and product details, including stock levels and recent movements.

### Product Management
This screen allows you to add, view, and edit products in the system.

### Warehouse Management
Manage different warehouse locations where your products are stored.

## Technologies Used
- **Flask**: Python-based web framework used to build the application.
- **MySQL**: Database for storing product and warehouse information.
- **Bootstrap**: CSS framework for responsive design.
- **JavaScript (jQuery)**: Used for dynamic content management.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
