# Data Commons

## Overview

Data Commons is a web application built using React, designed to manage datasets, projects, and patient information. 

## Features

- **Authentication**: Users can log in and log out. Unauthorized access to specific routes is prevented.
- **Dataset Management**: Manage datasets with options to view all datasets or a single dataset.
- **Patient Management**: View and manage patient information.
- **Project Management**: View all projects or a single project, with a dashboard overview.
- **Responsive Design**: The application is designed to be responsive, providing a good user experience across different devices.

## Project Structure

The project is structured into several directories:

```plaintext
REDMANE_react.js/
│
├── public/                # Public assets like images, fonts, etc.
├── src/                   # Source code for the project
│   ├── actions/           # Redux action creators
│   │   └── authActions.js # Actions related to authentication
│   ├── assets/            # Assets like images and logos
│   │   └── logos/         # Logos used in the application
│   │   └── testjson/       # JSON files for testing 
│   ├── components/        # Reusable components
│   │   ├── Dashboard/     # Components related to the dashboard
│   │   ├── Dataset/       # Components related to datasets
│   │   ├── Patient/       # Components related to patients
│   │   ├── Project/       # Components related to projects
│   │   ├── Footer.jsx     # Footer component
│   │   ├── Login.jsx      # Login component
│   │   ├── LogOutButton.jsx # Log Out button component
│   │   └── ProjectSummary.jsx # Project summary component
│   │   └── ProtectedRoute.jsx # Component to protect routes based on authentication
│   │   └── Upload.jsx     # Register dataset component
│   ├── pages/             # Page components, categorized by functionality
│   │   ├── DatasetPage/   # Pages related to datasets
│   │   ├── PatientPage/   # Pages related to patients
│   │   └── ProjectPage/   # Pages related to projects
│   │   └── DashboardPage.jsx # Dashboard page
│   │   └── LoginPage.jsx  # Login page
│   │   └── ProjectSummaryPage.jsx # Project Summary Page
│   │   └── UploadPage.jsx # Upload Page
│   ├── reducers/          # Redux reducers to manage state
│   ├── App.jsx            # Main application component
│   ├── index.css          # Global styles
│   ├── index.js           # Entry point for React
│   ├── main.js            # Main entry point for Vite
│   ├── store.js           # Redux store configuration
├── .gitignore             # Git ignore file
├── package.json           # Project metadata and dependencies
├── vite.config.js         # Vite configuration file
└── README.md              # Project documentation
```

## Installation

### Prerequisites

- **Node.js**: Ensure you have Node.js installed (v14 or later).

### Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone git@github.com:WEHI-RCPStudentInternship/REDMANE_react.js.git
   cd REDMANE_react.js
   ```

2. **Install dependencies:**

   Using npm:
   ```bash
   npm install
   ```

3. **Start the development server:**

   Using npm:
   ```bash
   npm run dev
   ```
