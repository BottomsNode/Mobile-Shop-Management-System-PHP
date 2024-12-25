# Mobile Shop Management System

## Overview
The **Mobile Shop Management System** is a web-based application designed to streamline operations in a mobile shop. This system automates various tasks such as inventory management, order processing, customer registration, and billing. It enhances operational efficiency, reduces errors, and provides a seamless user experience.

## Features
- **Customer Management**:
  - Registration and login functionality.
  - Order history tracking.
- **Inventory Management**:
  - Real-time stock updates.
  - Alerts for low stock levels.
- **Order Management**:
  - Order placement and tracking.
  - Automated invoice generation.
- **Billing System**:
  - Error-free billing with tax and discount calculations.
- **Reporting and Analytics**:
  - Sales and inventory reports.
  - Data visualization for decision-making.

## Technology Stack
- **Frontend**:
  - HTML, CSS, JavaScript
- **Backend**:
  - PHP
- **Database**:
  - MySQL

## Prerequisites
To run this system, ensure you have the following installed:
- PHP 7.x or higher
- MySQL 5.7 or higher
- Apache Web Server
- A modern web browser (e.g., Chrome, Firefox)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mobile-shop-management.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mobile-shop-management
   ```
3. Import the database:
   - Open `phpMyAdmin` or any MySQL client.
   - Import the `database.sql` file located in the `db` folder.
4. Configure the database:
   - Open `config.php` and update the database credentials.
   ```php
   $db_host = 'localhost';
   $db_user = 'root';
   $db_pass = 'your_password';
   $db_name = 'mobile_shop';
   ```
5. Start the server:
   ```bash
   php -S localhost:8000
   ```
6. Open the application in your browser:
   ```
   http://localhost:8000
   ```

## Screenshots
### Home Page
![Admin Dashboard](https://github.com/BottomsNode/Mobile-Shop-Management-System-PHP/blob/main/image.png)
### Admin Dashboard
![Admin Dashboard](https://github.com/BottomsNode/Mobile-Shop-Management-System-PHP/blob/main/admin_dashboard.png)
### Product Page
![Product Management](https://github.com/BottomsNode/Mobile-Shop-Management-System-PHP/blob/main/product_page.png)
### Invoice PDF Generation
![Invoice Generation](https://github.com/BottomsNode/Mobile-Shop-Management-System-PHP/blob/main/invoice_pdf.png)

## Testing
- **Validation Testing**:
  - Ensures proper input validation and error handling.
- **Output Testing**:
  - Verifies accuracy of invoices, reports, and data updates.
- **User Acceptance Testing**:
  - Tested by shop owners and employees for usability and functionality.

## Limitations
- Limited mobile optimization.
- Basic reporting capabilities.
- Manual payment and delivery tracking.

## Future Enhancements
- Develop a mobile app for improved accessibility.
- Integrate advanced analytics for sales and inventory trends.
- Automate payment processing and delivery tracking.

## License
This project is licensed under the [MIT License](LICENSE).

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## Contact
For questions or support, please contact:
- **Name:** Nishit Shivdasani
- **Email:** nishitshiv2001@gmail.com

---
Thank you for using the Mobile Shop Management System! 🚀
