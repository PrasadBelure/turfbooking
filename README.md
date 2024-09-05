# Turf Booking Application

## Overview
This project is a **Turf Booking System** that allows users to browse available sports turfs, check the availability of time slots, and book a turf for various sports. The app handles booking, payment proof submission, and displays available time slots dynamically. It's built with **React**, **Node.js**, **Express**, and **MySQL**.

## Features
- View a list of available turfs with detailed information.
- Check availability for specific time slots.
- Book turfs for sports like Cricket, Football, and Badminton.
- Upload payment proof as part of the booking process.
- Dynamic availability status (booked slots marked in red).

## Technologies Used
- **Frontend**: React, Ant Design (for DatePicker and Card components)
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Axios**: For API requests
- **Moment.js**: For handling dates

## How to run the project 
- Clone the repo
- Install install dependencies for both the frontend (client) and backend (server).
- You will need to set up the MySQL database using XAMPP. Use the database file to create the database .
- Run the server file by npm start first and then the client file .

##Project Images 
- Login Page 
![image](https://github.com/user-attachments/assets/8d1becf5-efbd-442f-a475-f7e753374935)
- Home Page
  ![image](https://github.com/user-attachments/assets/93da5871-4ed4-4c12-a010-2cd9890ef3f4)
- Booking Page
  ![image](https://github.com/user-attachments/assets/7771ec03-46be-4125-887c-6dcf817dcac3)




## Project Structure

```bash
turfbooking/
├── client
│   ├── public
│   ├── src
│   │   ├── components
│   │   │   ├── AddTurf.js          # Page to add new turfs
│   │   │   ├── BookingPage.js      # Turf booking page
│   │   │   ├── Navbar.js           # Navigation bar
│   │   │   ├── Footer.js           # Footer component
│   │   │   ├── AboutUs.js          # About Us page
│   │   │   ├── Availability.js     # Page to show turf availability
│   │   │   ├── Bookings.js         # Page to show user bookings
│   │   │   ├── Carousel.js         # Carousel component for showcasing images
│   │   │   ├── Contact.js          # Contact page
│   │   │   ├── Login.js            # Login page
│   │   │   ├── ProfilePage.js      # User profile page
│   │   │   ├── Register.js         # User registration page
│   │   ├── App.js                  # Main application file
│   │   ├── index.js                # Entry point for React app
│   │   └── AppTurf.css             # Styling for turf components
│   ├── package.json
│   └── README.md
├── server
│   ├── server.js                   # Express server for handling API requests
├── database.sql                    # SQL file for creating necessary database schema

