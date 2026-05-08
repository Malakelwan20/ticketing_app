Professional Project Description

The Event Ticketing System is a full-stack web application designed to simplify the process of event management and online ticket booking. The platform enables users to explore available events, reserve tickets, and manage their bookings through an intuitive and responsive interface.

The system also provides administrative functionality for managing events, monitoring bookings, and controlling ticket availability. Developed using PHP and MySQL, the application demonstrates core web development concepts including authentication, database management, session handling, and dynamic content rendering.

This project is designed to run in a XAMPP environment and follows a structured and maintainable development approach suitable for academic projects and portfolio presentation.

📌 Key Features
User Features
Secure user registration and login
Browse and search available events
View detailed event information
Online ticket booking system
Automatic total price calculation
Booking confirmation and history tracking
User profile management
Secure logout functionality
Admin Features
Create, edit, and delete events
Manage event ticket capacity
View and monitor user bookings
Track booking and payment status
Maintain event records efficiently

🗄️ Database Design

The system is built using a relational database structure containing three primary tables:

Users Table

Stores account and authentication information for registered users.

Events Table

Stores event-related information including title, description, pricing, and seat capacity.

Bookings Table

Stores ticket reservation details linked to users and events through foreign keys.

⚙️ System Workflow
Users create an account or log into the platform.
Available events are displayed dynamically from the database.
Users select an event and reserve tickets.
The system calculates pricing automatically.
Booking information is stored securely in the database.
Users receive a booking confirmation and can review reservations from their profile.
🔒 Security & Validation

The application implements several security practices including:

Session-based authentication
Password hashing
Form input validation
SQL injection prevention
Restricted page access for unauthorized users
