

# Bookstore Application

A full-stack web application for managing a bookstore, built with the MERN stack (MongoDB, Express.js, React, Node.js) and styled with Tailwind CSS.

## Features

- **CRUD Operations:** Perform basic Create, Read, Update, and Delete operations for managing books.
- **MERN Stack:** Utilizes MongoDB for data storage, Express.js for server-side logic, React for the user interface, and Node.js for the backend.
- **Responsive Design:** Styled with Tailwind CSS for a modern and responsive user interface.

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/wreckster1507/bookstore.git
   ```

2. Navigate to the project directory:

   ```bash
   cd bookstore
   ```

3. Install dependencies for both frontend and backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

### Configuration

1. Create a `.env` file in the `backend` folder with the following content:

   ```
   MONGODB_URI=your_mongodb_uri
   ```

   Replace `your_mongodb_uri` with your actual MongoDB connection string.

### Running the Application

1. Start the backend server:

   ```bash
   cd backend
   npm run dev
   ```

2. Start the frontend development server:

   ```bash
   cd frontend
   npm run dev
   ```

3. Open your browser and visit [http://localhost:3000](http://localhost:3000) to access the Bookstore application.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues.


```
