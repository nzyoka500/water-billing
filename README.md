# Water Billing & Customer Management System (WBCMS)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PHP Version](https://img.shields.io/badge/PHP-7.4%2B-blue.svg)](https://www.php.net/)
[![Database](https://img.shields.io/badge/Database-MySQL-orange.svg)](https://www.mysql.com/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

## Overview
The **Water Billing & Customer Management System (WBCMS)** is a **full-stack web application** built to help water service providers digitize and simplify customer management, meter reading, billing, and reporting.

The system reduces manual work by automating billing workflows, organizing customer records, and providing a dashboard for monitoring operational and revenue data.

This project demonstrates my ability to build **practical business systems** that solve real-world operational challenges.


## Project Highlights
- Built a **full-stack billing and customer management system**
- Automated **meter reading and bill generation workflows**
- Implemented **client registration, billing history, and dashboard reporting**
- Added **authentication, analytics, and admin tools**
- Designed for **small to medium utility/service providers**


## Why I Built This
Many small and medium service providers still rely on **manual records, spreadsheets, and paper-based billing**, which often leads to delays, billing errors, and poor record management.

I built this system to provide a more **organized, accurate, and efficient digital solution** for managing customer accounts, meter readings, and billing operations.


## My Role
I designed and developed this project as a **full-stack web application**, focusing on:

- Backend logic with **PHP**
- Database design and data handling with **MySQL**
- Frontend UI using **HTML, CSS, Bootstrap, and JavaScript**
- Billing workflow automation
- Dashboard analytics and reporting
- Authentication and admin management features


## Core Skills Demonstrated
- Full-stack web development
- CRUD operations
- Authentication & access control
- Database design & management
- Billing logic implementation
- Business process automation
- Dashboard and analytics development
- Responsive UI development
- Technical documentation


## Key Features

### Client Management
- **Unique Account Number Generation**  
  Automatically generates sequential account numbers using the format `AC-###/YYYY`.

- **Customer Profile Management**  
  Manage customer names, phone numbers, addresses, and account status.

- **Search & Record Tracking**  
  Easily search and manage customer records from the system.

### Billing & Metering
- **Meter Reading Tracking**  
  Capture current and previous readings to calculate water consumption.

- **Automated Bill Generation**  
  Generate bills automatically based on meter usage and configured billing rates.

- **Billing History**  
  Maintain a complete billing history for every customer.

### Dashboard & Analytics
- **Operational Dashboard**  
  View total customers, active bills, and revenue summaries in one place.

- **Charts & Visual Insights**  
  Uses **ApexCharts** for clear data visualization and reporting.

### Administrative Tools
- **Secure Authentication**  
  Login and registration system for staff/admin users.

- **System Settings**  
  Configure billing rates and key system settings.

- **Reports**  
  Generate reports for customer records, billing, and revenue tracking.


## Tech Stack

### Backend
- PHP (Vanilla PHP)
- MySQL

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript (ES6)

### Data Visualization
- ApexCharts

### Development Environment
- Apache
- XAMPP / WAMP / MAMP


## Screenshots

| 1. Login | 2. Registration |
| :---: | :---: |
| ![Login](./screenshot/Login.png) | ![Registration](./screenshot/Register.png) |

| 3. Dashboard Overview | 4. Client Registration |
| :---: | :---: |
| ![Dashboard](./screenshot/Dashboard.png) | ![Registration Modal](./screenshot/addClient.png) |

| 5. Clients List | 6. Billing Interface |
| :---: | :---: |
| ![Clients](./screenshot/Clients.png) | ![Billing](./screenshot/Billing.png) |


## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/nzyoka10/water-billing.git
```

### 2. Move Project to Server Directory
Move the project folder to your local server directory.

Example for XAMPP:
```bash
C:/xampp/htdocs/wbcms
```

### 3. Start Local Server
Start the following services from your local server environment:

- **Apache**
- **MySQL**

### 4. Create Database
- Open **phpMyAdmin**
- Create a new database named:

```sql
wbcms
```

### 5. Import Database
Import the SQL file found inside the:

```bash
/database
```

folder.

### 6. Configure Database Connection
Go to the `config/` folder and update your database credentials:

- Host
- Username
- Password
- Database name

### 7. Run the Project
Open your browser and visit:

```bash
http://localhost/water-billing
```


## Project Structure

```text
├── config/          # Database connection settings
├── css/             # Custom stylesheets
├── database/        # SQL export files
├── docs/            # Project documentation
├── img/             # UI assets and logos
├── inc/             # Reusable components (Header, Footer, Sidebar)
├── js/              # Frontend logic and chart initializations
├── screenshot/      # Application preview images
└── *.php            # Core application modules (Billing, Clients, Dashboard)
```


## Possible Future Improvements
- SMS/email bill notifications
- PDF invoice export
- Online payment integration (e.g. M-Pesa)
- Role-based permissions for staff
- Customer self-service portal
- Monthly usage and billing reports export


## Contributing
> Contributions are welcome.

If you'd like to improve the system:

1. Fork the repository  
2. Create a feature branch  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add AmazingFeature"
   ```
4. Push to your branch  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request


## Author
**Eric Nzyoka**  
Software & Systems Developer  

- GitHub: [Nzyoka](https://github.com/nzyoka500)
- LinkedIn: [Eric Nzyoka](https://www.linkedin.com/in/ericnzyoka)
- Email: mnzyokaeric@gmail.com


## License
This project is licensed under the **MIT License**.