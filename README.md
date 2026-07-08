# AquaSense Dashboard

> A web-based monitoring and control dashboard for an underwater remotely operated vehicle (ROV), built to visualize real-time water quality data and remotely operate the vehicle through Firebase Realtime Database.

AquaSense Dashboard is an IoT-based web application developed to monitor water quality and control an underwater drone (ROV) in real time. The dashboard receives live sensor readings from the ROV, displays environmental conditions, and allows operators to remotely control the vehicle through a responsive web interface.

This project was developed as part of an academic IoT project that combines embedded systems, cloud databases, and modern web technologies into a single monitoring platform.

---

## Key Features

### Real-Time Monitoring

* Live monitoring of water quality parameters
* Temperature monitoring
* Total Dissolved Solids (TDS) monitoring
* Electrical Conductivity (EC) monitoring
* Automatic real-time data synchronization using Firebase Realtime Database

### Remote Vehicle Control

* Start and stop the ROV motors
* Forward and backward navigation
* Low-latency command synchronization between the dashboard and the underwater drone

### User Interface

* Secure authentication system
* Responsive dashboard for desktop devices
* Modern Glassmorphism-inspired interface
* Real-time sensor updates without page refresh

---

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Cloud Database

* Firebase Realtime Database

### Libraries & Tools

* Firebase SDK
* Font Awesome
* Google Fonts (Inter)

---

## System Architecture

```text
                    Underwater Drone (ROV)
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
   TDS Sensor         EC Sensor        Temperature Sensor
        │                  │                  │
        └──────────────────┴──────────────────┘
                           │
                    Arduino Controller
                           │
                           ▼
             Firebase Realtime Database
                   ▲                  │
                   │                  ▼
        Control Commands      Live Sensor Data
                   │                  │
                   └──────────┬───────┘
                              ▼
                    AquaSense Dashboard
```

---

## My Responsibilities

I primarily contributed to the software development and dashboard implementation while also assisting with hardware integration.

My responsibilities included:

* Designing and developing the complete monitoring dashboard.
* Integrating Firebase Realtime Database for real-time communication.
* Implementing live visualization of sensor data.
* Developing the web-based interface for controlling the underwater drone.
* Connecting frontend components with Firebase services.
* Assisting in Arduino integration and hardware assembly.
* Participating in sensor testing, calibration, and overall system validation.

---

## Challenges

Developing AquaSense required close collaboration between hardware and software components.

One of the main challenges was maintaining reliable real-time communication between the underwater drone and the dashboard while ensuring sensor readings remained synchronized with Firebase.

Another challenge involved integrating multiple sensors into a single monitoring interface and presenting the data in a way that was both informative and easy to understand.

Working on this project provided valuable experience in IoT development, cloud-based real-time databases, hardware integration, and dashboard design.

---

## Running the Project

This application uses Firebase SDK with ES Modules, so it must be served through a local web server instead of opening the HTML file directly.

### Prerequisites

* Visual Studio Code (recommended)
* Live Server extension or any local HTTP server
* Firebase project configuration

### Setup

1. Open the project folder.
2. Configure the Firebase project credentials.
3. Start a local web server (such as Live Server).
4. Open the application in your browser.

---

## Future Improvements

Potential enhancements for future development include:

* Additional water quality sensors.
* Historical data visualization and analytics.
* GPS-based location tracking.
* Mobile-friendly dashboard.
* User activity logging.
* Alert and notification system for abnormal sensor readings.

---

## Project Status

Academic Project

Developed as part of an Internet of Things (IoT) project to demonstrate real-time communication between an underwater ROV, cloud database, and web-based monitoring dashboard.
