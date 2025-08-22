# 🚖 Cab Booking and Rental Management System (C++ OOP Project)

A **console-based Cab Booking and Vehicle Rental System** developed in **C++** using Object-Oriented Programming (OOP) concepts.  
This project was created as part of the **OOPs Course Project at NIT Silchar**.

---

## 📌 Abstract
This system is designed to provide a **reliable offline platform** for booking cabs (Tuk-tuks, Taxis) and renting vehicles (Motorcycles, Hatchbacks, Sedans, SUVs).  
It empowers both **users** and **drivers** to register, log in, manage profiles, and view history securely — all while running in a **lightweight console environment** without internet dependency.  

Key highlights:
- Role-based access (User / Driver)
- Offline data storage via CSV files
- Secure login with password validation
- Dynamic ride allocation using the **Haversine formula** for distance calculation
- Flexible ride modes (Solo / Shared) & transparent rental cost calculation

---

## ✨ Features

### 👤 User Features
- Register and log in securely  
- Book a cab (Tuk-tuk or Taxi) with **distance-based fare**  
- Rent vehicles with **cost computed per day**  
- Choose Solo or Shared rides  
- View booking and rental history  
- Edit personal details and update passwords  

### 🚕 Driver Features
- Register and log in securely  
- Update live location dynamically  
- View assigned bookings  
- Manage profile and credentials  
- Track ride history  

### ⚙️ System Features
- Offline data storage using CSV files (`Users.csv`, `Drivers.csv`, `Bookings.csv`, etc.)  
- Password complexity enforcement (8+ chars, uppercase, lowercase, digit)  
- Input validation (email, phone, Aadhaar, etc.)  
- Exception handling for robust performance  
- Daily reset of driver locations at 4 AM to simulate realistic operations  

---

## 🛠️ Tech Stack

- **Language:** C++ (C++11 and above)  
- **Compiler:** GCC g++, Clang, MSVC  
- **IDE:** Visual Studio Code / Code::Blocks  
- **Data Storage:** CSV file handling (`fstream`, `stringstream`)  

---


## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/KunalRSangalge/Cab-Booking-And-Rental
