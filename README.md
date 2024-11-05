
# Airline Ticket Booking System

## Overview
This is a simple command-line and GUI-based application for booking airline tickets. Users can book tickets, cancel bookings, view ticket information, and see all bookings. The application uses Tkinter for the graphical user interface and CSV files for data storage.

## Features
- **Book Tickets**: Users can view available seats and book a ticket for a specific seat number.
- **Cancel Tickets**: Users can cancel a booked ticket using the ticket number.
- **View Ticket Information**: Users can retrieve information about a booked ticket, including cancellation time if applicable.
- **View All Bookings**: Users can see all booked tickets and their statuses.
- **Update Ticket**: Users can change the seat number for a booked ticket.
- **Available Seats Display**: The application always shows the number of available seats.
- **Data Persistence**: All bookings and cancellations are saved to a CSV file, ensuring data is retained even after the application is closed.

## Requirements
- Python 3.x
- Tkinter (usually comes pre-installed with Python)
- No additional libraries are required.

## Getting Started
1. Clone or download the repository.
2. Ensure you have Python 3 installed on your machine.
3. Run the `airline_booking_system.py` script to start the application.
4. Follow the on-screen prompts to book, cancel, or view tickets.

## Usage
- Enter the seat number you wish to book and click the "Book Ticket" button.
- To cancel a ticket, enter the ticket number and click the "Cancel Ticket" button.
- To view ticket information, enter the ticket number and click the "View Ticket Information" button.
- Click "View All Bookings" to see a list of all bookings.
- Enter a new seat number to update the ticket information if needed.

## Saving Data
The application automatically saves all bookings and cancellations to a CSV file named `airline_new.csv` when the window is closed or when the "Save and Exit" button is clicked.

## License
This project is open-source and free to use. Feel free to modify and distribute it as needed.

## Acknowledgments
- Thanks to the Python community for the resources and libraries that made this project possible.

