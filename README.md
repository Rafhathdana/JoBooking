# Jobooking Online Booking App

Jobooking is an online booking application that allows users to easily find and book hotels, view available rooms, and make reservations. This app provides a user-friendly interface for both customers and administrators, offering seamless hotel management and booking experiences.

## Features

### Admin Functionality

- **Login:** Admins can log in securely to access the admin dashboard.
- **Hotel Management:** Create, update, and manage hotels with detailed information.
- **Categories:** Categorize hotels for easy navigation and search.
- **Room Management:** Add and manage rooms within hotels, including availability and pricing.
- **Location:** Define and manage hotel locations and places.
- **User Management:** Admins can manage user accounts and access permissions.

### User Functionality

#### User-Friendly Interface

- **Login:** Users can log in to their accounts to access personalized features.
- **Hotel Search:** Browse hotels, view available rooms, and check room details.
- **Hotel Booking:** Book hotels, Book available rooms, and check room details.
- **User Registration:** Users can create accounts with photos for a personalized experience.

## Dependencies

- **@mui/material:** React components for faster and easier web development.
- **axios:** HTTP client for making API requests.
- **react-router-dom:** Declarative routing for React.js.
- **mongoose:** MongoDB object modeling tool.
- **jsonwebtoken:** JSON Web Token implementation for authentication.
- **bcrypt:** Password hashing library for added security.

## Environment Variables

- **PORT:** Port number for the server (default: 8800)
- **MONGODB_URI:** MongoDB database connection URI
- **JWT_SECRET:** Secret key for JSON Web Token encryption

## How to Use

```bash
# Clone the repository
git clone <repository-url>
cd JoBooking
cd JoBooking-client
# Install Dependencies
npm install
cd JoBooking-admin
# Install Dependencies
npm install
cd JoBooking-server
# Install Dependencies
npm install
 
# Set Environment Variables for JoBooking-server
# Create a .env file in the root directory and set the required variables

# Run the Application
npm start
Contributing
We welcome contributions to improve Jobooking! Feel free to fork the repository, create pull requests, and report issues. Please follow the contribution guidelines when submitting changes.

License
This project is licensed under the MIT License.
