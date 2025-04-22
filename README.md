# Movie Ticket Booking System

A modern web application for booking movie tickets, built with Python Flask and HTML/CSS.

## Features

- Browse available movies
- View movie details and showtimes
- Select seats and book tickets
- Responsive design for all devices
- Booking confirmation system

## Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd movie-ticket-booking
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Start the Flask development server:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

## Project Structure

```
movie-ticket-booking/
             
├── requirements.txt    # Python dependencies
├── static/
│   └── style.css      # CSS styles
└── templates/
    ├── base.html      # Base template
    ├── index.html     # Home page
    ├── movie_detail.html  # Movie details page
    ├── booking.html   # Booking form
    └── booking_confirmation.html  # Booking confirmation page
```

## Database

The application uses SQLite as the database, which is automatically created when you first run the application. The database file will be created as `movies.db` in the project root directory.

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Commit your changes
4. Push to your branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 