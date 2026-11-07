# Service Lagbe

A web-based home service booking platform where customers can find and book trusted technicians, technicians can manage their jobs, and service bookings are organized in one place.

## Developer

| | |
|---|---|
| **Name** | Md. Emon Hossain |
| **Student ID** | [223014123] |
| **Department** | Computer Science and Engineering (CSE) |
| **University** | University of Liberal Arts Bangladesh (ULAB) |

## Tech Stack

- **Backend:** PHP
- **Database:** MySQL / MariaDB
- **Frontend:** HTML, CSS, JavaScript
- **Local server:** XAMPP (Apache + MySQL)

## User Roles and Features

### Customer
- Sign up, log in and manage profile and address
- Browse services by category and view service details
- Book a service by choosing date, time slot, area size and service type
- Automatic price calculation
- Booking confirmation and booking history
- Leave a rating and review after a service is completed
- Contact form

### Technician
- Personal dashboard with assigned jobs
- Accept or reject job requests
- View customer details, address, schedule and notes for each job
- Track pending, confirmed and completed jobs

## Booking Flow

1. Customer selects a service and submits a booking
2. A technician is assigned to the request
3. Technician accepts or rejects the job
4. The job is marked as completed after service
5. Customer leaves a review and the technician rating is updated automatically

## Setup (XAMPP)

1. Copy this folder into `C:\xampp\htdocs\`
2. Copy `config.sample.php` to `config.php` and fill in your own settings
3. Start **Apache** and **MySQL** in the XAMPP Control Panel
4. Open `http://localhost/phpmyadmin`, click **Import**, choose `ServiceLagbe.sql` and click **Go**
5. Open `http://localhost/ServiceLagbe-main/`

## Author

Md. Emon Hossain, CSE, University of Liberal Arts Bangladesh (ULAB)