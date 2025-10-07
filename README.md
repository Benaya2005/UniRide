# UniRide 🚗🎓

## Overview  
**UniRide** is a campus-based ride-sharing and on-demand transport application designed to make mobility easier for students, staff, and visitors.  
It allows users to **offer rides or request seats** for trips both **inside and outside the campus**, helping to reduce traffic, save time, and promote sustainable transport.

UniRide provides two main user roles:
- **Riders** – who can browse available rides, book a seat, or schedule a future ride.
- **Drivers** – who can publish ride offers, accept requests, and manage their trips.

The app also includes an **Admin** interface to manage users, verify drivers, and monitor system activity.

---

## Features

### Rider Features
- Register or log in via email confirmation.  
- View and filter available ride offers in real time.  
- Choose between **inside campus** or **outside campus** rides.  
- Book a ride, specifying pickup and destination points.  
- Automatically calculated fare based on distance and number of passengers.  
- Option to **schedule rides** in advance.  
- Receive live **notifications** (driver accepted, on the way, arrived).  
- Contact drivers via WhatsApp.  
- View driver details (name, car model, license plate).  
- Leave reviews and report misconduct.  
- Real-time driver location tracking during active rides.

### Driver Features
- Register by providing and verifying **license, insurance, student/staff ID**, and car details.  
- Create and publish **ride offers** (pickup, destination, available seats, departure time).  
- View and accept ride requests from riders.  
- Manage scheduled rides and view trip history.  
- View basic rider information after accepting a booking.  
- Real-time location sharing with accepted riders.  
- Cancel rides (limited cancellations before suspension).  
- View **earnings, trip history, and reviews**.  
- Report riders for misconduct.

### Admin Features
- Manage rider and driver accounts (add, edit, delete, suspend).  
- Verify driver documents.  
- Review and manage user complaints or reports.  
- Access booking history and activity logs.  
- Moderate reviews and ratings.  
- Generate statistics (rides completed, revenue, active users).  
- Configure system settings such as fares, pickup points, and cancellation rules.

---

## Non-Functional Requirements
- **Performance:** Handles up to 500 concurrent users with <2s delay in ride updates.  
- **Security:** All data encrypted; HTTPS communication; verified drivers only.  
- **Reliability:** 99% uptime during campus hours, daily backups.  
- **Usability:** Intuitive mobile UI; riders can book a ride in under 3 minutes.  
- **Portability:** Cross-platform (Android and iOS) built with **React Native**.  

---

## Tech Stack (Suggested)
- **Frontend:** React Native / Flutter  
- **Backend:** Firebase (Authentication, Firestore, Cloud Functions, Storage)  
- **APIs:** Google Maps API for routing and distance calculation  
- **Notifications:** Firebase Cloud Messaging  
- **Database:** Firebase Firestore  

---

## Installation (Development Mode)
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/uniride.git
   cd uniride
