# Park and Ride: Smart Parking & Last-Mile Connectivity Solution

A smart urban mobility platform that simplifies your commute.  
This system enables real-time parking spot booking, last-mile shuttle/cab integration, and AI-powered dynamic pricing — all while supporting offline access and system fault-tolerance.

---

## Tech Stack

| Layer      | Tech Used                           |
|------------|-------------------------------------|
| Frontend   | HTML, CSS, JavaScript               |
| Backend    | Spring Boot (Java)                  |
| Database   | MySQL                               |
| Auth       | JWT (JSON Web Tokens)               |
| Hosting    | [To Deploy: Netlify / Vercel / Railway] |
| Deployment | Localhost (Spring Boot)             |

---

## Features

### 1. Seamless Parking Booking
- Search and pre-book parking slots near metro stations  
- Real-time availability with dynamic spot assignment  
- Contactless entry using QR codes / License Plate Recognition (LPR)

### 2. Cab & Last-Mile Shuttle Integration
- Book cabs, shuttles, or e-rickshaws from your phone  
- On-demand or scheduled rides with AI-based route optimization  
- Integration with metro cards and digital wallets

### 3. Availability Conflict Resolution
- IoT-based live tracking of slot availability  
- No-show auto-cancellation  
- Dynamic reallocation of free slots to avoid booking clashes

### 4. Dynamic Pricing Engine
- Peak-hour surge pricing and off-peak discounts  
- AI-based demand forecasting and route adjustment  
- Subscription plans and loyalty rewards

### 5. Offline Mode Support
- View bookings and QR passes without internet  
- Auto-sync on network restoration  
- Preloaded voice-guided parking directions

---

## Implementation Highlights

- JWT-based secure authentication  
- Modular structure using OOP principles  
- AI-driven pricing and routing logic  
- In-memory caching for optimized performance  
- Error handling with structured logging  
- Monitored and tested under edge cases
---


src/
├── controller/
├── service/
├── repository/
├── model/
├── config/       # JWT Auth configs
├── static/       # Frontend HTML/CSS/JS
└── resources/
    └── application.properties
## Future Improvements
-Use Firebase for real-time updates
-Add mobile app support (React Native / Flutter)
-Integrate real-world LPR system using OpenCV
-Enable Redis caching layer for better performance
