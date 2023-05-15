# WiFi-based Indoor Positioning System

This project is a React Native application that estimates the user's position inside a building based on the WiFi signals available to their device. 

## Project Overview

The project uses WiFi signal strengths to estimate the user's indoor location. The underlying principle is that WiFi signal strength (RSS) decreases predictably with distance from the access point, which can be used to estimate the device's position relative to multiple known access points.

## Features

- Scans available WiFi networks and collects RSS data.
- Estimates the user's position based on trilateration or fingerprinting.
- Displays the estimated position on a simple indoor map.

## Technologies Used

- React Native for mobile app development.
- Flask and Python for backend server.
- Bootstrap for UI design.

## How to Install and Run

### Prerequisites

- Node.js and npm installed.
- Android Studio with a configured emulator or a physical Android device.

### Installation Steps

1. Clone the repository: `git clone https://github.com/YourGithubUsername/YourRepositoryName.git`
2. Navigate into the project directory: `cd YourRepositoryName`
3. Install dependencies: `npm install`
4. Start the server: `npm start`

### Running the Application

To run the application on an Android device or emulator, use the command: `npx react-native run-android`


## Contact

Yifan - wyfaxyj@example.com
