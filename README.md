# In-and-Out-Laundry

## Project Overview

In & Out Laundry is a laundry collection, cleaning and delivery management system developed as part of a Software Development WIL project.

The system consists of a website and an Android mobile application. Both applications are designed to allow customers to book laundry services, make payments, track orders and manage their accounts.

## Website

The website is the web-based part of the system.

It allows customers to:

* View available laundry services
* View pricing
* Register and log in
* Book a laundry service
* Provide pickup and delivery details
* View booking information
* Make payments
* Track laundry orders
* View previous orders
* Manage their profile
* Contact the business

The website also includes an admin dashboard for managing customers, bookings, services, payments and orders.

Technologies used:

* HTML
* CSS
* JavaScript
* ASP.NET Core Web API
* SQL Server / Azure SQL

## Mobile Application

The mobile application is the Android version of the In & Out Laundry system.

It provides similar functionality to the website but is designed specifically for mobile devices.

Customers can:

* Create an account
* Log in
* View services
* Create laundry bookings
* Enter pickup and delivery details
* Make payments
* Track orders
* View order history
* Receive notifications
* Manage their profile
* Contact support

Technologies used:

* Kotlin
* Android Studio
* Android Jetpack
* MVVM
* Retrofit
* Room Database

## Backend API

The backend provides communication between the website, mobile application and database.

The API is responsible for:

* Customer authentication
* Customer management
* Service information
* Booking management
* Payment information
* Order management
* Order tracking
* Notifications

Technology used:

* ASP.NET Core Web API
* C#

## Database

The database stores and manages the information used by the system.

Main tables include:

* Customers
* Services
* Bookings
* Payments
* Orders
* ContactMessages
* Notifications

The database is designed using relational database principles and normalisation.

Technology used:

* SQL Server
* Azure SQL

## Testing

Testing is used to make sure that the system works correctly.

Tests cover areas such as:

* Customer registration
* Login
* Booking validation
* Price calculations
* Payment status
* Order tracking
* Order status updates
* API functionality

Unit testing is also used to test individual parts of the application.

## Design and Documentation

Figma is used to create the wireframes and user interface designs.

The project documentation includes:

* Project plan
* Sitemap
* Wireframes
* Requirements analysis
* UML diagrams
* Class diagrams
* Entity Relationship Diagram
* System architecture
* Database design
* Testing documentation
* User documentation

## Project Management

Azure DevOps is used to manage the development process.

The team uses a Kanban board to manage tasks through stages such as:

* To Do
* In Progress
* Testing
* Done

GitHub is used for source control and storing the project code.

## Project Structure

The project is divided into different sections:

```text
InAndOutLaundry/
│
├── website/
│   ├── html/
│   ├── css/
│   ├── js/
│   └── images/
│
├── mobile_app/
│   └── Android Kotlin project
│
├── backend/
│   └── ASP.NET Core Web API
│
├── database/
│   └── SQL scripts
│
├── tests/
│   └── Unit and integration tests
│
└── docs/
    └── Project documentation
```

## Team

The project is developed by a team of three Software Development students.

Each member is responsible for different areas of the project, including development, mobile application development, UI/UX design, testing and documentation.

## Project Goal

The goal of the project is to develop a simple and reliable digital laundry management system that allows customers to book laundry services, make payments and track their orders while allowing the business to manage its customers and orders.
