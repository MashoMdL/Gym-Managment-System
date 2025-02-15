![pulselogo](https://github.com/user-attachments/assets/940f22e4-bd04-404b-a7c7-8d877de5d61a)
# Gym Management System


Welcome to the **Gym Management System**. This is a full-stack web application designed to manage gym operations efficiently. It includes features for both the admin and staff, as well as providing a customer registration system. The system is built using **PHP**, **MySQL**, and front-end technologies such as **HTML**, **CSS**, and **JavaScript**.

## Features

### Admin Panel

- **Manage Members**: Add, remove, or update gym members.
- **Manage Gym Equipment**: Track and manage the gym's equipment inventory.
- **Attendance**: Monitor staff and member attendance records.
- **Manage Customer Progress**: Track the fitness progress of members.
- **Member's Status**: View the current status of members (active/inactive).
- **Payments**: Manage payments, including invoices and membership fees.
- **Announcements**: Admin can post announcements for gym members.
- **Staff Management**: Manage staff roles, permissions, and activities.
- **Reports**: Generate reports on member activities, payments, and other gym metrics.

### Dashboard Overview

- **Active Members**: 16 active members.
- **Registered Members**: 18 registered members.
- **Total Earnings**: $3340 in total earnings.
- **Announcements**: View and manage up to 4 announcements.
- **Services Report**: View detailed service usage reports.

### Staff Panel

- **Login**: Staff can log in to manage their daily tasks and member interactions.
- **Appointment Scheduling**: Staff can schedule and manage member appointments.

### Customer Registration

- **Sign-up**: New customers can register and become gym members.
- **View Membership Details**: Customers can view and update their membership details.


## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Libraries/Tools**: Bootstrap, jQuery

## Screenshots

### 1. Admin Login Page
![image](https://github.com/user-attachments/assets/4c418f7e-230c-4bae-a624-8dae6b092242)

### 2. Staff Login Page
![image](https://github.com/user-attachments/assets/f459c05d-ab54-4a56-a29f-4e9e2517491b)

### 3. Customer Register Page
![image](https://github.com/user-attachments/assets/f060c555-9a1f-45d2-bb63-23b9f34290db)

### 4. Admin Dashboard Overview
![screencapture-localhost-gymsystem-admin-index-php-2025-02-15-11_57_53](https://github.com/user-attachments/assets/6da7a01c-3995-46c3-b50b-4f792d8cbe12)
## Installation

To set up this project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/gym-management-system.git
    ```

2. Navigate into the project folder:
    ```bash
    cd gym-management-system
    ```

3. Set up your **MySQL** database:
    - Create a new database and import the provided `.sql` file to set up the tables.

4. Configure the database connection:
    - Edit the `config.php` file with your **MySQL** credentials.

5. Start your local server and open the app in your browser:
    - For example, using XAMPP or MAMP to run PHP.

## Usage

- **Admin Login**: Navigate to `/index.php` and enter your admin credentials to access the dashboard.
- **Staff Login**: Navigate to `/staff/index.php` to log in as a staff member.
- **Customer Register**: New customers can register through the `/customer.php` page.

## Contributing

We welcome contributions to improve the functionality and features of the Gym Management System! If you'd like to contribute, please fork the repository, create a new branch, and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

