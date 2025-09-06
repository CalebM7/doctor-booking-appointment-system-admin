# Doctor Booking System - Admin Panel

This is the frontend for the admin and doctor panel of the Doctor Booking System. It is built with React and Vite.

## Description

This project provides two interfaces:
- **Admin Interface:** For managing doctors, and viewing all appointments and patients.
- **Doctor Interface:** For doctors to manage their appointments, and view their earnings and profile.

## Features

### Admin
- Dashboard with an overview of total doctors, appointments, and patients.
- View a list of all appointments with the ability to cancel them.
- Add new doctors to the system.
- View a list of all doctors.

### Doctor
- Dashboard with an overview of total earnings, appointments, and patients.
- View a list of their appointments with the ability to mark them as complete or cancel them.
- Manage their profile.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/doctor-booking-system.git
   ```
2. Navigate to the admin directory:
   ```bash
   cd doctor-booking-system/admin
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.
Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

### `npm run build`

Builds the app for production to the `dist` folder.

### `npm run lint`

Lints the project files.

### `npm run preview`

Previews the production build.

## Dependencies

- [axios](https://axios-http.com/)
- [react](https://reactjs.org/)
- [react-dom](https://reactjs.org/docs/react-dom.html)
- [react-router-dom](https://reactrouter.com/)
- [react-toastify](https://fkhadra.github.io/react-toastify/introduction)

## Folder Structure

```
/src
|-- /assets
|-- /components
|   |-- Navbar.jsx
|   `-- Sidebar.jsx
|-- /context
|   |-- AdminContext.jsx
|   |-- AppContext.jsx
|   `-- DoctorContext.jsx
|-- /pages
|   |-- Login.jsx
|   |-- /Admin
|   |   |-- AddDoctor.jsx
|   |   |-- AllAppointments.jsx
|   |   |-- Dashboard.jsx
|   |   `-- DoctorsList.jsx
|   `-- /Doctor
|       |-- DoctorAppointments.jsx
|       |-- DoctorDashboard.jsx
|       `-- DoctorProfile.jsx
|-- App.jsx
|-- index.css
`-- main.jsx
```