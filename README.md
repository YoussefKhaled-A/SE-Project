# 🎡 Online Amusement Park Reservation System

This project is a Java-based software engineering system that allows users (parents, children, and admins) to interact with a virtual amusement park environment. The system includes ticket reservations, activity scheduling, child location tracking via RFID, feedback submission, and more — all through an interactive GUI.

##  Overview

The system was developed as part of our Software Engineering II course at the British University in Egypt. It aims to provide an intuitive platform for managing amusement park operations for families and staff while ensuring child safety, booking flexibility, and payment integration.

##  Key Features

-  **Ticket Reservation**  
  Reserve tickets for individual visits, group trips, or birthday events with customizable options and time slots.

-  **Manage Reservations**  
  Edit or cancel existing bookings directly through the dashboard.

-  **Schedule Activities**  
  Children can join over 100 fun and educational role-playing activities based on real-life professions.

-  **Manage Activities**  
  Parents can rearrange or remove scheduled activities and receive real-time UI updates.

-  **Locate Children via RFID**  
  Track your child's real-time location using RFID wristbands.

- 🗺 **Interactive Map**  
  Explore the park and activity zones through a digital navigation system.

-  **Payment Module**  
  Pay via cash or Visa with support for discounts and cashback using the **Decorator Pattern**.

-  **Feedback Mechanism**  
  Submit and view feedback about the park experience. Admins can respond directly through the system.

-  **Admin Controls**  
  Admins can ban users, manage feedback, and ensure system safety.

## ⚙️ Technologies Used

- Java (Swing/AWT for GUI)
- OOP Principles (Encapsulation, Inheritance, Polymorphism)
- MySQL (for persistence)
- Design Patterns:
  - **Observer** (Activity UI Updates)
  - **Decorator** (Payments)
  - **Strategy** (Child Location Tracking)
  - **State** (Activity Scheduling)


## Modules Implemented by Me (Youssef Khaled)

- `Activity`, `Feedback`, `Ticket` (Entities + Controllers + UI)
- Real-time UI using **Observer Pattern**
- Feedback Submission + Reply Flow

## Test Coverage

Includes unit test cases for:
- Admin Sign-Up
- Customer Login
- Payment with Decorator
- Reservation Flow
- RFID Location Tracking

## How to Run

1. Clone the repo  
   `git clone https://github.com/YoussefKhaled-A/SE-Project.git`

2. Open in your preferred IDE (e.g., IntelliJ or Eclipse)

3. Compile all `.java` files

4. Run `Main.java` (or appropriate entry point)  

5. Use sample credentials to log in as Parent/Admin/Child
