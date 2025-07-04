# BookSmart - Online Book Store Management System

A comprehensive management system for bookstores that handles inventory, sales, employee management, and reporting.

## Features

- **Book Inventory Management**
  - Add, update, and delete book records
  - Track stock levels with low stock alerts
  - Categorize books and manage metadata

- **Sales Management**
  - Record and track book sales
  - Calculate real-time profits
  - Customer purchase history

- **Employee Management**
  - Manage employee records
  - Handle payroll and commissions
  - Track employee performance

- **Reporting & Analytics**
  - Generate daily, weekly, and monthly reports
  - Sales trends and projections
  - Inventory turnover analysis

## Tech Stack

- **Frontend**
  - React with TypeScript
  - Tailwind CSS for styling
  - Recharts for data visualization
  - React Router for navigation

- **Backend**
  - Node.js with Express
  - MongoDB for database (configured but using mock data for demo)
  - JWT for authentication

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```
git clone https://github.com/yourusername/booksmart.git
cd booksmart
```

2. Install dependencies
```
npm install
```

3. Start the development servers
```
npm run dev:full
```

This will start both the React frontend and the Express backend concurrently.

- Frontend will be available at: http://localhost:5173
- Backend API will be available at: http://localhost:5000

### Login Information

For demo purposes, you can use any email and password combination to log in.

## Project Structure

```
/src                  # Frontend React code
  /components         # Reusable UI components
  /contexts           # React contexts for state management
  /layouts            # Page layout components
  /pages              # Page components
  /services           # API service functions
  
/server               # Backend Node.js/Express code
  /routes             # API route handlers
  
/public               # Static assets
```

## Features To Be Implemented

- Connect to real MongoDB database
- Implement proper authentication with password hashing
- Add advanced reporting features
- Email notifications for low stock
- Barcode scanning for inventory management

## License

This project is licensed under the MIT License.# booksmart
