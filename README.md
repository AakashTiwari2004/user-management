# User Management System

## Overview

The **User Management System** is a backend application developed using **Django** and **Django REST Framework (DRF)**.  
It provides RESTful APIs for managing users, including creation, retrieval, updating, and deletion of user records.  
The system ensures data integrity through validations such as unique email addresses and leverages Django's admin panel for administrative management.

---

## Features

- RESTful APIs for user CRUD operations
- Email uniqueness validation
- Admin panel integration
- Ready for deployment on cloud platforms
- Efficient and scalable design

---

## Technologies

- Python 3.12  
- Django 4.x  
- Django REST Framework  
- SQLite (default, can be replaced with PostgreSQL/MySQL)  
- Gunicorn (for production deployment)  
- Redis/Celery (optional for asynchronous tasks)  

---

## Installation Instructions

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/AakashTiwari2004/user-management.git
cd user-management

