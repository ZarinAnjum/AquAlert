# AquAlert: Water Quality Monitoring Dashboard

AquAlert is a web-based water quality monitoring dashboard designed to provide users with real-time (simulated) analysis of water parameters like pH, Iron, and Bacteria levels. It features a modern, futuristic dark theme, user authentication, and a history of past analyses.

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Pages](#pages)
- [Contact](#contact)

## Getting Started

To run this application locally, simply download or clone the repository and open the `login.html` file in your web browser. Due to the use of `localStorage` for user data and analysis history, it's recommended to open these files from a local web server (e.g., using Live Server VS Code extension) to avoid potential browser security restrictions for local file access.

## Features
- **Futuristic Dark Theme:** A sleek, high-contrast dark interface with glassmorphism effects.
- **User Authentication:** Secure registration and login using `localStorage`.
- **Real-time Analysis (Mocked):** Simulate water quality analysis with immediate feedback.
- **Personalized Settings:** View your registered account details.
- **Analysis History:** Keep track of all your past water quality reports.
- **Report Generation:** Generate formal reports for critical water conditions.

## Pages

### `register.html`
Allows new users to create an account by providing their name, email, phone number, and password. Credentials are saved to `localStorage`.

### `login.html`
Provides a secure login interface for registered users. On successful login, users are redirected to the dashboard.

### `dashboard.html`
The main operational hub for AquAlert. Here, users can input sensor readings to get an instant water quality analysis. It stores analysis history locally and allows generation of reports.

### `settings.html`
Displays the registered user's name, email, and phone number.

### `history.html`
Shows a chronological list of all past water quality analyses performed by the user.

## Contact

For any inquiries, please contact us at: [promiseitsnotfake@gmail.com](mailto:promiseitsnotfake@gmail.com)

&copy; All rights reserved by The Maevricks