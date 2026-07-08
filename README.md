# AquaSense Dashboard

AquaSense is a web-based dashboard designed for monitoring and controlling an underwater drone (ROV). It provides real-time sensor data visualization and a remote control interface for drone maneuverability.

## Features

- **Authentication System**: Secure login portal to restrict unauthorized access.
- **Real-Time Telemetry**: Live monitoring of water quality metrics utilizing Firebase Realtime Database:
  - **TDS (Total Dissolved Solids)**: Measures the concentration of dissolved particles in the water.
  - **EC (Electrical Conductivity)**: Monitors the water's ability to conduct electricity.
  - **Temperature**: Tracks the operational environment temperature.
- **Drone Control Interface**: Web-based control panel to maneuver the drone:
  - Motor Start/Stop
  - Forward/Backward directional controls
- **Firebase Integration**: Full synchronization with Firebase Realtime Database for seamless two-way communication between the web client and the underwater drone hardware.
- **Modern UI/UX**: Glassmorphism design system with responsive layouts for optimal viewing across devices.

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6)
- **Backend/Database**: Firebase Realtime Database (v10.7)
- **Typography & Icons**: Google Fonts (Inter), Font Awesome

## Getting Started

### Prerequisites

An active internet connection is required to fetch the Firebase SDK and Font Awesome assets via CDN.

### Installation & Execution

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/aquasense-dashboard.git
   ```
2. Open the project directory.
3. Due to the use of ES modules for Firebase, the application must be served over HTTP/HTTPS rather than the local `file://` protocol. 
   - We recommend using [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code or any local development server.
4. Navigate to `index.html` through your local server.
5. Use the following demo credentials to access the dashboard:
   - **Username**: `admin` | **Password**: `drone123`
   - **Username**: `operator` | **Password**: `aqua2026`

## Screenshots

*(Include screenshots of your login and dashboard interfaces here)*
- `Screenshot of Login Page`
- `Screenshot of Main Dashboard`

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

## License

This project is licensed under the MIT License.
