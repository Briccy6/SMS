# School Management System

![School Management System](https://user-images.githubusercontent.com/your-image-url)

## Overview

The **School Management System** is a web-based application built with **Laravel 11** and **JavaScript**, with a focus on creating a responsive and user-friendly interface using **Tailwind CSS**. This system is designed to manage various school operations, including student enrollment, class scheduling, attendance tracking, and grade management. It also features role-based access control to differentiate between users like **admins**, **teachers**, and **students**.

## Features

### General
- **Role-Based Access Control (RBAC)**: Different roles (Admin, Teacher, Student) with specific permissions.
- **Dashboard**: Interactive dashboard displaying key information.
- **Notifications**: Email notifications for important updates using SMTP.

### Admin Features
- Manage students, teachers, and classes.
- Assign subjects to teachers.
- View and print student reports.
- Generate attendance reports.

### Teacher Features
- Record and view student attendance.
- Assign and grade assignments.
- Enter student marks and generate reports.

### Student Features
- View personal class schedule.
- Check grades and progress.
- Submit assignments online.

## Technologies Used

- **Laravel 11**: Backend framework used for handling the logic of the application.
- **JavaScript**: Frontend interactivity and dynamic components.
- **Tailwind CSS**: Styling framework to create a modern, responsive UI.
- **MySQL**: Database to store all system data, including user information, grades, and attendance.
- **SMTP**: Email notification system for sending alerts and updates.

## Installation

### Prerequisites

Before setting up the project, make sure you have the following installed:
- PHP 8.1+
- Composer
- Node.js & npm
- MySQL (or any other supported database)
- Laravel 11

### Steps to Install

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Briccy6/school-management-system.git
   cd school-management-system
