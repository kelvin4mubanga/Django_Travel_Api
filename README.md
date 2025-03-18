# Travel API - Django REST Framework

## Overview
The Travel API allows users to explore different travel destinations, view details, and book trips. Built using Django REST Framework, it provides endpoints for managing destinations, bookings, and user profiles.

## Features
- List all available travel destinations
- View detailed information about a destination
- Book a trip to a destination
- Manage user reservations
- Cancel a booking

## Technologies Used
- Django  
- Django REST Framework  
- Pillow (for image handling)  
- SQLite (default database)  

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/kelvin4mubanga/travel-api.git
cd travel-api
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
```bash
python manage.py migrate
```

### 5. Run the Server
```bash
python manage.py runserver
```
The API will be available at **http://127.0.0.1:8000/**.

---

## Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/api/destinations/` | List all travel destinations |
| GET | `/api/destinations/<id>/` | Get details of a specific destination |
| POST | `/api/bookings/` | Book a trip to a destination |
| GET | `/api/bookings/<id>/` | View booking details |
| DELETE | `/api/bookings/<id>/` | Cancel a booking |

---

## License
MIT License

## Contact
For any inquiries, reach out via kelvinmubanga045@gmail.com.
