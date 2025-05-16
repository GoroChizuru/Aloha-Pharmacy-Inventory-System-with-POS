# Aloha-Pharmacy-Inventory-System-with-POS
Event Driven X Application Development

# Aloha Pharmacy - Inventory and POS System

A modern pharmacy management system built with Django REST Framework backend and React frontend.

## Project Structure

The project consists of two main components:

### Backend (Django REST Framework)

Located in the `/backend` directory

- Built with Django and Django REST Framework
- SQLite database
- RESTful API endpoints for:
  - Inventory management
  - Sales and transactions
  - User authentication
  - Reports and analytics

### Frontend (React)

Located in the `/inventory-pos` directory

- Built with React and Vite
- Modern UI with Tailwind CSS
- Features:
  - Real-time inventory tracking
  - Point of Sale interface
  - Sales reporting
  - User authentication

## Prerequisites

- Python 3.x
- Node.js (Latest LTS version)
- npm or yarn

## Installation

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```bash
   python manage.py migrate
   ```
5. Create admin user:
   ```bash
   python manage.py createsuperuser
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd inventory-pos
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

### Backend

```bash
cd backend
python manage.py runserver
```

The backend server will run on http://localhost:8000

### Frontend

```bash
cd inventory-pos
npm run dev
```

The frontend development server will run on http://localhost:5173

## Features

- Inventory Management
  - Stock tracking
  - Low stock alerts
  - Product categorization
- Point of Sale
  - Quick sales processing
  - Receipt generation
  - Payment processing
- User Management
  - Role-based access control
  - User authentication
- Reporting
  - Sales reports
  - Inventory reports
  - Analytics dashboard

## Technologies Used

### Backend

- Django
- Django REST Framework
- SQLite
- JWT Authentication

### Frontend

- React
- Vite
- Tailwind CSS
- Axios
- React Router
- JWT Decode




