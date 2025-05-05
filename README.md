# Inventory Management System (IMS)

## Project Description

The **Inventory Management System (IMS)** is a web application built with **Flask** for managing products, warehouses, and product movements in a business. It provides functionality for adding, updating, and tracking inventory across different warehouses and categories. The system supports product movement features such as sales, purchases, and transfers.

## Features

- **Landing Page:** A welcoming page that provides a brief overview and navigation options.
- **Dashboard:** A user-friendly interface that gives an overview of inventory, products, movements, and warehouses.
- **Product Management:** Add and edit products with category and warehouse details.
- **Warehouse Management:** Create and manage warehouses.
- **Product Movement:** Track and manage product movements (sale, purchase, and transfer).
- **Reports:** View reports for product balances and movements in different warehouses.

## Technologies Used

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Flask
- **Database:** MySQL
- **Version Control:** Git

## Installation

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.x
- MySQL server
- Git

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/Santhosh1015/Inventory_Management_System.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Inventory_Management_System
    ```

3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    On Windows:
    ```bash
    venv\Scripts\activate
    ```

    On macOS/Linux:
    ```bash
    source venv/bin/activate
    ```

5. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

6. Set up the MySQL database by creating the necessary tables:
    - Create a MySQL database for the system.
    - Update the database connection settings in the application configuration file.

7. Run the Flask app:
    ```bash
    flask run
    ```

8. Visit `http://127.0.0.1:5000` in your browser to start using the system.

## Usage

- **Landing Page:** When you access the application, you will be greeted with a landing page that provides an overview of the system and basic navigation options.
- **Dashboard:** After logging in, the dashboard will provide you with an overview of the inventory, recent product movements, warehouse details, and quick links to navigate to products, movements, and reports.
- Navigate to **Products** to view, add, or edit products.
- Go to **Warehouses** to manage warehouse details.
- Use **Movement** to add product movements (sale, purchase, transfer).
- Check **Reports** for an overview of product balances across warehouses.

## Screenshots

Below are some screenshots of the system:

### Landing Page

![Landing Page Screenshot](path/to/your/image/landing_page.png)

### Dashboard

![Dashboard Screenshot](path/to/your/image/dashboard.png)

### Product Management

![Product Management Screenshot](path/to/your/image/product_management.png)

### Movement Management

![Movement Management Screenshot](path/to/your/image/movement_management.png)

### Report View

![Report Screenshot](path/to/your/image/report.png)

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add feature'`).
4. Push to your fork (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
