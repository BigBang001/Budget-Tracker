# Financial Tracking App

## Overview

This is a simple financial tracking app that allows users to input their expenses and income, categorize their spending, and get basic insights into their financial habits. The app is built with a Node.js backend and a React frontend, connected to a MongoDB database for data storage.

## Features

- **Add Transactions**: Input income or expense transactions with details like amount, category, and date.
- **Categorize Spending**: Organize transactions into predefined categories.
- **Data Visualization**: View charts showing income and expenses trends for better insights.
- **Responsive Design**: Optimized for both desktop and mobile use.

## Tech Stack

### Backend:
- **Node.js**: Server-side JavaScript runtime.
- **Express**: Web framework for building RESTful APIs.
- **MongoDB**: NoSQL database for storing transaction data.
- **Mongoose**: ODM library for MongoDB data modeling.

### Frontend:
- **React**: JavaScript library for building user interfaces.
- **Axios**: For making HTTP requests.
- **Chart.js**: Library for creating dynamic charts.

## Prerequisites

Before you start, ensure you have the following installed:
- **Node.js** (>=14.0.0)
- **npm** (Node Package Manager)
- **MongoDB** (local or cloud-based instance)

## Getting Started

### Backend Setup

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file and add your MongoDB connection string:
   ```
   MONGO_URI=your_mongodb_connection_uri
   ```

4. Start the backend server:
   ```bash
   node server.js
   ```

   The backend will run on `http://localhost:3001`.

### Frontend Setup

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

   The frontend will run on `http://localhost:3000`.

## How to Use

1. **Add a Transaction**:
   - Go to the "Add Transaction" form in the app.
   - Enter the transaction details (amount, category, and date).
   - Click "Add" to save the transaction.

2. **View Dashboard**:
   - Navigate to the "Dashboard" page to see visual insights of your spending and income over time.

## Future Enhancements

- **User Authentication**: Implement secure user login with JWT tokens.
- **Advanced Analytics**: Include pie charts and category breakdowns for better financial insights.
- **Budgeting Features**: Add a feature for users to set and track monthly budgets.
- **Mobile App**: Develop a mobile version using React Native for on-the-go tracking.

## Acknowledgments

- Inspired by simple finance management apps.
