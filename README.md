# Expense Tracker

## Table of Contents
1. [Project Title and Description](#project-title-and-description)
2. [Features Overview](#features-overview)
3. [Tech Stack & Prerequisites](#tech-stack--prerequisites)
4. [Installation Guide](#installation-guide)
5. [Usage Instructions](#usage-instructions)
6. [Configuration](#configuration)
7. [Contributing Guidelines](#contributing-guidelines)
8. [License Information](#license-information)
9. [Contact/Support Information](#contactsupport-information)

## Project Title and Description
Expense Tracker is a web application that helps users manage their finances by tracking income and expenses. The application provides a user-friendly interface to add, edit, and delete transactions, and visualize financial data through charts and tables.

## Features Overview
- User authentication with email/password and Google sign-in
- Add, edit, and delete income and expense transactions
- View current balance, total income, and total expenses
- Visualize financial data with charts
- Export and import transactions as CSV files
- Search and filter transactions
- Responsive design for mobile and desktop

## Tech Stack & Prerequisites
- **Frontend**: React, Ant Design, ApexCharts, React Router, React Toastify
- **Backend**: Firebase Authentication, Firestore
- **Other**: PapaParse for CSV handling

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher) or yarn

## Installation Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/Mohamed-Jameel-13/Expense-Tracker1.git
   cd Expense-Tracker1
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a Firebase project and configure Firebase Authentication and Firestore.

4. Add your Firebase configuration to `src/firebase.js`:
   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_AUTH_DOMAIN",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_STORAGE_BUCKET",
     messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
     appId: "YOUR_APP_ID",
   };
   ```

5. Start the development server:
   ```bash
   npm start
   ```

## Usage Instructions
1. Sign up or log in using email/password or Google sign-in.
2. Add income and expense transactions using the provided forms.
3. View your current balance, total income, and total expenses on the dashboard.
4. Visualize your financial data with charts.
5. Export and import transactions as CSV files.
6. Search and filter transactions using the search bar and filters.

## Configuration
- Firebase configuration: Add your Firebase project configuration to `src/firebase.js`.
- Customize the application by modifying the components and styles in the `src` directory.

## Contributing Guidelines
1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License Information
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact/Support Information
For support or inquiries, please contact [Mohamed Jameel](mailto:smartjameel823@gmail.com).
