# Limupa Store – Full Stack eCommerce Platform

## Overview

Limupa Store is a full-stack eCommerce platform for digital products built using HTML5, CSS3, Bootstrap 4 (frontend) and Python Django (backend). It provides a complete online shopping experience including product browsing, cart management, secure checkout, and order processing.

The project is designed with scalability, clean architecture, and real-world eCommerce functionality in mind.

## Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 4
- JavaScript
- jQuery
- Font Awesome
- Google Fonts

### Backend
- Python
- Django
- Django ORM
- Django Admin Panel

### Database
- SQLite (development)
- PostgreSQL / MySQL (production-ready)

## Key Features

### User System
- User Registration and Login
- Secure Authentication
- User Profile Management
- Password Reset Flow

### eCommerce Features
- Product Listing and Categories
- Product Detail Pages
- Add to Cart and Remove from Cart
- Cart Quantity Update
- Checkout System
- Order Placement

### Order Management
- Order History
- Order Status Tracking
- Admin Order Control

### Admin Panel
- Manage Products (CRUD)
- Manage Categories
- Manage Orders
- Manage Users
- Dashboard Overview

### UI/UX Features
- Fully Responsive Design
- Pixel Perfect UI
- Clean and Structured Layout
- Smooth Animations
- Cross-Browser Support
- Fast Loading Pages

## Project Structure

limupa-store/
├── accounts/        # User authentication and profiles
├── products/        # Product management
├── cart/            # Shopping cart logic
├── orders/          # Order processing
├── core/            # Base settings and common logic
├── templates/       # HTML templates (frontend)
├── static/          # CSS, JS, images
├── media/           # Uploaded files
├── manage.py
└── requirements.txt

## Installation Guide

### Clone Repository
git clone https://github.com/your-username/limupa-store.git
cd limupa-store

### Create Virtual Environment
python -m venv env

### Activate Environment

Linux/macOS:
source env/bin/activate

Windows:
env\Scripts\activate

### Install Dependencies
pip install -r requirements.txt

### Apply Migrations
python manage.py migrate

### Create Superuser
python manage.py createsuperuser

### Run Server
python manage.py runserver

## Pages Included

- Home Page
- Shop Page
- Product Detail Page
- Cart Page
- Checkout Page
- Login and Register Pages
- User Dashboard
- Blog Pages
- About Us Page
- Contact Page

## Future Improvements

- Payment Gateway Integration (Stripe / PayPal)
- Product Reviews and Ratings
- Wishlist System
- Coupon and Discount System
- Email Notifications
- Advanced Admin Analytics
- REST API using Django REST Framework
- Docker Deployment

## Author

Awais Ali Shah

Python Django Developer  
Full Stack Web Developer  
Backend and API Specialist

## License

This project is for educational and portfolio purposes. Ensure proper licensing if used for commercial deployment.
