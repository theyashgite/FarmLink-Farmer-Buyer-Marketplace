# FarmLink – Farmer-Buyer Marketplace System

FarmLink is a web-based marketplace application designed to connect farmers and buyers through a digital platform. Farmers can list their crops, while buyers can browse available agricultural products and send purchase requests.

## Features

- User registration and login
- Separate farmer and buyer dashboards
- Add, view, and delete crop listings
- Browse and search available crops
- Submit purchase requests with quantity and offered price
- View and manage incoming purchase requests
- Accept or reject purchase requests
- MySQL database integration

## Technology Stack

**Frontend**
- React.js
- Vite
- JavaScript
- HTML and CSS

**Backend**
- Node.js
- Express.js

**Database**
- MySQL

## Project Structure

The project contains frontend and backend code, along with the configuration and database files used by the application.

Update this section to match the actual folder structure of your project.

## Getting Started

### Prerequisites

Install the following software:

- Node.js and npm
- MySQL Server
- Git

### Installation

1. Clone this repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Open the project folder in VS Code.

3. Install frontend dependencies by opening the frontend directory in the terminal and running:

   ```bash
   npm install
   ```

4. Install backend dependencies by opening the backend directory in another terminal and running:

   ```bash
   npm install
   ```

5. Configure the required environment variables for the backend and database connection. Do not upload passwords or secret credentials to GitHub.

6. Create the required MySQL database and tables using your project's database schema or SQL export.

7. Start the backend using the command configured in its `package.json`. For example, if the project has a `start` script:

   ```bash
   npm start
   ```

8. Start the frontend using the command configured in its `package.json`. For a standard Vite project:

   ```bash
   npm run dev
   ```

9. Open the local URL shown in the frontend terminal.

## Database

MySQL is used to store user details, crop listings, and purchase request information.

If a database export is included in the repository, use that SQL file to set up the database.

## Future Enhancements

- AI-based crop price prediction
- Online payment integration
- Order and delivery management
- Notifications for purchase requests
- Multilingual support

## Project Purpose

This project demonstrates the use of frontend development, backend APIs, and relational database management to build an agricultural marketplace application.

## Author

**Your Name**

Replace this line with your name and add your GitHub profile link if desired.
