# Hostel Management System

A comprehensive hostel management system built with Python and CustomTkinter, featuring user authentication, room management, maintenance requests, and more.

## Features

- User Authentication (Login, Register, Forgot Password)
- User Dashboard
  - View Room Details
  - Make Rent Payments
  - Submit Maintenance Requests
  - Submit Exit Requests
- Admin Dashboard
  - Add Rooms
  - Assign Rooms
  - View Reports
  - Manage Leave Requests
  - Generate PDF Reports

## Prerequisites

- Python 3.8 or higher
- MySQL Server
- pip (Python package installer)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hostel-management-system.git
cd hostel-management-system
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Configure MySQL:
- Install MySQL Server if not already installed
- Update the database connection settings in `database/db_connection.py` if needed:
  - host (default: "localhost")
  - user (default: "root")
  - password (default: "admin")

## Running the Application

1. Make sure MySQL Server is running

2. Run the main application:
```bash
python main.py
```

## Usage

### Admin Access
- Email: admin@example.com
- Password: admin123

### Student Access
- Register a new account through the registration form
- Use registered email and password to login

## Project Structure

```
hostel-management-system/
├── assets/
│   └── UI/            # UI assets (images)
├── database/
│   └── db_connection.py
├── screens/
│   ├── login.py
│   ├── register.py
│   ├── forgot_password.py
│   ├── user_dashboard.py
│   ├── admin_dashboard.py
│   └── ...
├── utils/
│   ├── auth.py
│   ├── helpers.py
│   └── pdf_generator.py
├── main.py
├── requirements.txt
└── README.md
```

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License. 
=======
# Housing-Management-Application
Housing management system for Brightstay Housing
>>>>>>> 3f84a45a06b35a4548564e973868a17fbaf9bf56
