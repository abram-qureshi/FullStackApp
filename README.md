# ReadVine

ReadVine is a comprehensive web application that combines a robust back-end with an interactive front-end to deliver a seamless user experience. This project demonstrates features such as user authentication, book management, and dynamic search capabilities.

---

## Features

- **User Authentication**: Secure sign-up, login, and password recovery functionalities.
- **Book Listings**: Users can add, edit, delete, and display books available for exchange or lending.
- **Book Search**: Search and filter books by title, author, genre, availability, and location.
- **Profile Management**: Each user has a profile that includes their listed books.

---

## Tech Stack

### Front-End
- **Framework**: React.js
- **Styling**: CSS
- **State Management**: React Hooks

### Back-End
- **Framework**: Django REST Framework
- **Database**: PostgreSQL
- **Authentication**: JWT-based authentication

---

## Installation

### Prerequisites
- Python (version 3.8+)
- Node.js and npm
- PostgreSQL

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/abram-qureshi/FullStackApp.git
   cd FullStackApp
   ```

2. **Set up the backend**:
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Create a virtual environment and activate it:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate
     ```
   - Install the required packages:
     ```bash
     pip install -r requirements.txt
     ```
   - Set up the database:
     ```bash
     python manage.py makemigrations
     python manage.py migrate
     ```
   - Run the development server:
     ```bash
     python manage.py runserver
     ```

3. **Set up the frontend**:
   - Navigate to the frontend directory:
     ```bash
     cd ../frontend
     ```
   - Install the dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

4. **Access the application**:
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:8000/api/`

---
