# Events and Adventures App

This is a starter mobile app for the "Events and Adventures" singles group. Built with React Native and Node.js.

## Features
- View a calendar of events (members)
- Sign up for events (members)
- Add new events (admins)
- Simple backend API with Express and MongoDB

## Setup Instructions

### Mobile App (Frontend)
1. Navigate to the frontend folder:
    ```
    cd frontend
    npm install
    npx react-native run-android
    ```
    (or `run-ios` on Mac)

2. Make sure your backend is running (see below) and the IP is correctly set in `CalendarScreen.js` and `AdminDashboard.js`.

### Backend Server
1. Navigate to the backend folder:
    ```
    cd backend
    npm install
    node server.js
    ```
2. Ensure MongoDB is running locally on your system.

## Notes
- Android emulators should use `http://10.0.2.2:3000` to connect to the backend.
- Replace this with your actual IP address for physical devices.

## License
MIT
