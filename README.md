🚆 Train Booking System
A simple console-based Train Booking System in C++ that allows users to sign up, log in, manage trains, and book tickets. Data is stored in plain text files for simplicity.

📌 Features
Authentication System

Sign up as a new admin

Login for existing users

Train Operations

Add new train entries

View all trains

Search for a specific train by train number

Ticket Booking

Book tickets by route

View all bookings

Search bookings by booking ID

User Guidance

Initial instructions provided for user interaction

🧱 Project Structure
├── main.cpp        # Main logic and UI
├── work.h          # Classes for Auth, TrainOperations, TicketBooking
├── Authentication.txt  # Stores admin login info
├── TrainFile.txt       # Stores train data
├── Tickets.txt         # Stores ticket bookings

🧾 How to Use
Compile and Run

Use any C++ compiler (e.g., g++, Visual Studio):


g++ main.cpp -o TrainBookingSystem
./TrainBookingSystem

Startup Flow

App begins with a User Guide

Choose between:

Sign up as new admin

Login with existing credentials

Dashboard Menu

After logging in:

Train Operations

Add/View/Search trains

Booking Options

Book/View/Search bookings

Logout to switch users

✍️ Input Rules
Use - instead of spaces in inputs (e.g., New-Delhi instead of New Delhi)

Ensure valid and correct entries

Double-check the text files (TrainFile.txt, Tickets.txt) for stored data

💡 Notes
File operations use simple .txt files to store data persistently.

This project is best suited for learning purposes.

Uses system("CLS") and getch() for UI interaction (Windows-specific).

Data is not encrypted—for production-level systems, consider using secure databases and hashed credentials.

📚 Dependencies
<iostream>, <fstream>, <windows.h>, <string.h>, <conio.h>

Tested on Windows systems only due to reliance on Windows-specific headers.
