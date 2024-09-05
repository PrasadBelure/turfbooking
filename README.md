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

## Project Structure

```bash
├── public
├── src
│   ├── components
│   │   ├── AddTurf.js      # Page to add new turfs
│   │   ├── BookingPage.js  # Turf booking page
│   │   ├── Navbar.js       # Navigation bar
│   │   ├── Footer.js       # Footer component
│   ├── App.js
│   ├── index.js
│   └── AppTurf.css         # Styling for turf components
├── package.json
└── README.md
