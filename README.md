# BAUHINIA Clothing Order Tracking System

## Project Overview

The BAUHINIA Clothing Order Tracking System is designed to streamline the inventory management and order processing for BAUHINIA, a prominent clothing brand. This online solution replaces the old manual system and automates the workflow to enhance efficiency and accuracy in handling customer orders and inventory.

<p align="center">
  <img src="dashboard.png" alt="System Overview">
</p>

## Features

### Customer Features
- **Customer Registration and Sign-In**: Allows customers to register with details including name, email address, delivery address, password, and contact numbers. Registered customers can log in using their email address and password.
- **Browse Products**: Customers can view the product catalog, check availability, and add items to their cart.
- **Checkout**: Displays the total amount to be paid and redirects customers to confirm their billing details. Payment is processed via cash on delivery.

### Staff Features
- **Staff Registration and Sign-In**: Staff members can register and log in to access the system.
- **Daily Reports**:
  - **Order Report**: Production Manager can generate daily reports of all requested orders.
  - **Product Availability Report**: Production Manager can generate daily reports on product availability.
- **Inventory Management**:
  - **Add/Update Items**: Inventory Clerk can add new items and update existing item details.
- **Monthly Income Report**: Chief Accountant can generate monthly income reports.

### Access Levels
- **Report Only**: View reports without any modification rights.
- **Update Only**: Modify existing records without the ability to delete.
- **Update and Delete**: Modify and delete records.
- **Complete System Access**: Full access to all features and administrative functions.

## Technologies Used
- **Language**: PHP
- **Database**: MySQL
- **Server**: XAMPP
- **IDE**: VS Code

## Getting Started
1. Clone the repository: `git clone https://github.com/Nava-stack/bauhinia-clothstore-php.git`
2. Set up XAMPP and start the Apache and MySQL services.
3. Import the database schema from `database/BAUHINIA.sql` into MySQL.
4. Configure database connection settings in `config/database.php`.
5. Open the project in VS Code and run it on your local server.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
